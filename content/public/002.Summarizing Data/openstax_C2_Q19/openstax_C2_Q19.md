---
title: Depth of Hunger
topic: Summarizing Data
author: Gavin Kendal-Freedman
source: 2.2
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
- 2.1.1.7
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
workspaceFiles:
- student.R
- .Rprofile
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
        title: Depth of Hunger
        color: purple
        color_inst: The color of the frequency polygon should be purple.
      table: |-
        <table style="width:100%">
        <tr>
        <th>Depth of Hunger</th>
        <th>Frequency</th>
        </tr><tr>
        <td>230–259</td>
        <td>28</td>
        </tr><tr>
        <td>260–289</td>
        <td>13</td>
        </tr><tr>
        <td>290–319</td>
        <td>6</td>
        </tr><tr>
        <td>320–349</td>
        <td>7</td>
        </tr><tr>
        <td>350–379</td>
        <td>0</td>
        </tr><tr>
        <td>380–409</td>
        <td>0</td>
        </tr><tr>
        <td>410–439</td>
        <td>1</td>
        </tr>
        </table>
      _workspace_files:
      - name: data.csv
        contents: |
          Depth of Hunger,Frequency
          230–259,28
          260–289,13
          290–319,6
          320–349,7
          350–379,0
          380–409,0
          410–439,1
      autograding:
        std_plot: std_fd07rq8j_plot.png
        ref_plot: ref_pjbbwd8y_plot.png
      _images:
      - label: Your Frequency Polygon
        filename: std_fd07rq8j_plot.png
        part: Check graph is similar to expected graph
      - label: Expected Frequency Polygon
        filename: ref_pjbbwd8y_plot.png
        part: Check graph is similar to expected graph
      _autograder_files:
      - path: /grade/tests/data.csv
        contents: RGVwdGggb2YgSHVuZ2VyLEZyZXF1ZW5jeQoyMzDigJMyNTksMjgKMjYw4oCTMjg5LDEzCjI5MOKAkzMxOSw2CjMyMOKAkzM0OSw3CjM1MOKAkzM3OSwwCjM4MOKAkzQwOSwwCjQxMOKAkzQzOSwxCg==
      - path: /grade/student/data.csv
        contents: RGVwdGggb2YgSHVuZ2VyLEZyZXF1ZW5jeQoyMzDigJMyNTksMjgKMjYw4oCTMjg5LDEzCjI5MOKAkzMxOSw2CjMyMOKAkzM0OSw3CjM1MOKAkzM3OSwwCjM4MOKAkzQwOSwwCjQxMOKAkzQzOSwxCg==
---
# {{ params.vars.title }}

## Part 1

Construct a frequency polygon from the frequency distribution for the 50 highest ranked countries for depth of hunger.

{{{ params.table }}}

<pl-card title="Instructions">

Please open the RStudio workspace below and edit the `student.R` script to complete the following task:

Please write R code that generates a frequency polygon with the following properties:

- The title of the frequency polygon should be 'Depth of Hunger'.
- The x-axis label should be 'Depth of Hunger'.
- The y-axis label should be 'Frequency'.
- {{ params.vars.color_inst }}
- Do *not* overplot your line graph.

When you are ready to test your code, click the "Grade" button.

Once you are satisfied with the plot your code generates, make sure the script file is saved in RStudio.

To submit your answer after saving it in RStudio, come back to this page and select "Save & Grade" or "Save only" at the bottom of the page.

*Note: You should not need to use `ggplot2` for this question, and you are not advised to do so, as it may interfere with the autograder.*

</pl-card>

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)