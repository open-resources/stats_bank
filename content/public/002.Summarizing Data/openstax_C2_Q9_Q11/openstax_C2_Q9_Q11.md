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
        <th>High School</th>
        <th>Science competition population (%)</th>
        <th>Overall student population (%)</th>
        </tr><tr>
        <th>Alabaster</th>
        <td>14.8</td>
        <td>26.4</td>
        </tr><tr>
        <th>Concordia</th>
        <td>33.8</td>
        <td>19.5</td>
        </tr><tr>
        <th>Genoa</th>
        <td>18.3</td>
        <td>23.1</td>
        </tr><tr>
        <th>Mocksville</th>
        <td>11.7</td>
        <td>7.4</td>
        </tr><tr>
        <th>Tynneson</th>
        <td>6.4</td>
        <td>16.0</td>
        </tr><tr>
        <th>West End</th>
        <td>15.0</td>
        <td>7.6</td>
        </tr>
        </table>
      graph_instructions:
      - The plot should have a main title of 'Overall Student Population from Each
        School'.
      - The x-axis should be labeled 'Proportion (%)'.
      - The y-axis should be labeled 'School'.
      - The bars should be appropriately labelled.
      - The bars should be colored darkgreen.
      - The bars should have a purple border.
      - The bars should have a density of 6.
      - The plot should be horizontal.
      description: David County has six high schools. Each school sent students to
        participate in a county-wide science competition. The table below shows the
        percentage breakdown of competitors from each school, and the percentage of
        the entire student population of the county that goes to each school. Construct
        a bar graph that shows the county-wide population percentage of students at
        each school.
      autograding:
        col1:
        - Alabaster
        - Concordia
        - Genoa
        - Mocksville
        - Tynneson
        - West End
        x:
        - '26.4'
        - '19.5'
        - '23.1'
        - '7.4'
        - '16.0'
        - '7.6'
        title: Overall Student Population from Each School
        xlab: Proportion (%)
        ylab: School
        color: darkgreen
        border: purple
        density: 6
        horiz: 'True'
        std_plot: std_u3chb3_p_plot.png
        ref_plot: ref_63ctod45_plot.png
      _images:
      - label: Your Bar Plot
        filename: std_u3chb3_p_plot.png
        part: Check graph is similar to expected graph
      - label: Expected Bar Plot
        filename: ref_63ctod45_plot.png
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