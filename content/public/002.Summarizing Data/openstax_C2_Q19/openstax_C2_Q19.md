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
    params_vars_title: Depth of Hunger
    params_vars_color: darkgreen
    params_vars_color_inst: The color of the frequency polygon should be darkgreen.
    params_table: |-
      <table style="width:100%">
      <tr>
      <th>Depth of Hunger</th>
      <th>Frequency</th>
      </tr><tr>
      <td>230–259</td>
      <td>22</td>
      </tr><tr>
      <td>260–289</td>
      <td>12</td>
      </tr><tr>
      <td>290–319</td>
      <td>5</td>
      </tr><tr>
      <td>320–349</td>
      <td>8</td>
      </tr><tr>
      <td>350–379</td>
      <td>0</td>
      </tr><tr>
      <td>380–409</td>
      <td>2</td>
      </tr><tr>
      <td>410–439</td>
      <td>1</td>
      </tr>
      </table>
    params__workspace_files:
    - name: data.csv
      contents: |
        Depth of Hunger,Frequency
        230–259,22
        260–289,12
        290–319,5
        320–349,8
        350–379,0
        380–409,2
        410–439,1
    params_autograding_std_plot: std_j32r8vtd_plot.png
    params_autograding_ref_plot: ref_rch_m4dj_plot.png
    params__images:
    - label: Your Frequency Polygon
      filename: std_j32r8vtd_plot.png
      part: Check graph is similar to expected graph
    - label: Expected Frequency Polygon
      filename: ref_rch_m4dj_plot.png
      part: Check graph is similar to expected graph
    params__autograder_files:
    - path: /grade/tests/data.csv
      contents: RGVwdGggb2YgSHVuZ2VyLEZyZXF1ZW5jeQoyMzDigJMyNTksMjIKMjYw4oCTMjg5LDEyCjI5MOKAkzMxOSw1CjMyMOKAkzM0OSw4CjM1MOKAkzM3OSwwCjM4MOKAkzQwOSwyCjQxMOKAkzQzOSwxCg==
    - path: /grade/student/data.csv
      contents: RGVwdGggb2YgSHVuZ2VyLEZyZXF1ZW5jeQoyMzDigJMyNTksMjIKMjYw4oCTMjg5LDEyCjI5MOKAkzMxOSw1CjMyMOKAkzM0OSw4CjM1MOKAkzM3OSwwCjM4MOKAkzQwOSwyCjQxMOKAkzQzOSwxCg==
---
# {{ params_vars_title }}

## Part 1

Construct a frequency polygon from the frequency distribution for the 50 highest ranked countries for depth of hunger.

{{{ params_table }}}

<pl-card title="Instructions">

Please open the RStudio workspace below and edit the `student.R` script to complete the following task:

Please write R code that generates a frequency polygon with the following properties:

- The title of the frequency polygon should be 'Depth of Hunger'.
- The x-axis label should be 'Depth of Hunger'.
- The y-axis label should be 'Frequency'.
- {{ params_vars_color_inst }}
- Do *not* overplot your line graph.

When you are ready to test your code, click the "Grade" button.

Once you are satisfied with the plot your code generates, make sure the script file is saved in RStudio.

To submit your answer after saving it in RStudio, come back to this page and select "Save & Grade" or "Save only" at the bottom of the page.

*Note: You should not need to use `ggplot2` for this question, and you are not advised to do so, as it may interfere with the autograder.*

</pl-card>

### pl-submission-panel

If you correctly created the plot, but were marked incorrect by the autograder, please contact your TA for manual review of your submission.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)