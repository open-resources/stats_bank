---
title: Bar Graphs
topic: Summarizing Data
author: Gavin Kendal-Freedman
source: 2.1
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: true
showCorrectAnswer: false
gradingMethod: External
workspaceOptions:
  image: prairielearn/workspace-rstudio
  port: 3939
  args: ''
  rewriteUrl: false
  home: /home/rstudio/workspace
  gradedFiles:
  - student.R
externalGradingOptions:
  enabled: true
  image: bluesy1/grader-r
  entrypoint: python3 /r_autograder/entrypoint.py
  timeout: 60
outcomes:
- 2.1.1.4
difficulty:
- medium
randomization:
- undefined
taxonomy:
- undefined
span:
- undefined
length:
- undefined
tags:
- GKF
- autograder
assets: null
workspaceTemplates:
- student.R.mustache
- .Rprofile.mustache
autogradeTestFiles:
- solution.R
- test_01.R
part1:
  type: workspace
  gradingMethod: External
myst:
  substitutions:
    params:
      vars:
        title: Bar Graphs
      table: |-
        <table style="width:550px">
        <tr>
        <th>Season</th>
        <th>Number of students</th>
        <th>Proportion of population (%)</th>
        </tr><tr>
        <th>Spring</th>
        <td>5</td>
        <td>14</td>
        </tr><tr>
        <th>Summer</th>
        <td>7</td>
        <td>20</td>
        </tr><tr>
        <th>Autumn</th>
        <td>18</td>
        <td>51</td>
        </tr><tr>
        <th>Winter</th>
        <td>5</td>
        <td>14</td>
        </tr>
        </table>
      graph_instructions:
      - The plot should have a main title of 'Birthdays in Each Season'.
      - The x-axis should be labeled 'Number of students'.
      - The y-axis should be labeled 'Season'.
      - The bars should be appropriately labelled.
      - The bars should be colored blue.
      - The bars should have a red border.
      - The bars should have a density of 3.
      - The plot should be horizontal.
      description: The students in Ms. Ramirez’s math class have birthdays in each
        of the four seasons. The table below shows the four seasons, the number of
        students who have birthdays in each season, and the proportion (%) of students
        in each group. Construct a bar graph showing the number of students.
      autograding:
        col1:
        - Spring
        - Summer
        - Autumn
        - Winter
        x:
        - 5
        - 7
        - 18
        - 5
        title: Birthdays in Each Season
        xlab: Number of students
        ylab: Season
        color: blue
        border: red
        density: 3
        horiz: 'True'
        std_plot: std_8if23fsp_plot.png
        ref_plot: ref_719xz14m_plot.png
      _images:
      - label: Your Bar Plot
        filename: std_8if23fsp_plot.png
        part: Check graph is similar to expected graph
      - label: Expected Bar Plot
        filename: ref_719xz14m_plot.png
        part: Check graph is similar to expected graph
---
# {{ params.vars.title }}
{{ params.description }}

{{{ params.table }}}

<pl-card title="Instructions">

Please open the RStudio workspace below and edit the `student.R` script to complete the following task:

Please write R code that generates a barplot with the following properties:

<ul>
{{# params.graph_instructions }}
  <li>{{.}}</li>
{{/ params.graph_instructions }}
</ul>

Note: You should not need to use `ggplot2` for this question, and you are not advised to do so, as it may interfere with the autograder.

Once you are satisfied with the plot your code generates, make sure the script file is saved in RStudio.

To submit your answer after saving it in RStudio, come back to this page and select "Save & Grade" or "Save only" at the bottom of the page.

</pl-card>

## Part 1

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)