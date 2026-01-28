---
title: Line Graphs
topic: Summarizing Data
author: Gavin Kendal-Freedman
source: original
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
- 2.1.1.7
difficulty:
- easy
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
        title: Line Graphs
        description: Several children were asked how many TV shows they watch each
          day. The results are shown in the table below.
        graph_title: Number of TV Shows watched each day
        x_axis: Number of TV Shows
        y_axis: Frequency
        overplotted: should
        style: o
        color: orange
      _workspace_files:
      - name: data.csv
        contents: |
          Number of TV Shows,Frequency
          0,9
          1,17
          2,39
          3,7
          4,3
      df: null
      autograding:
        std_plot: std_ig32a352_plot.png
        ref_plot: ref_jjxkzr3s_plot.png
        csv: |
          Number of TV Shows,Frequency
          0,9
          1,17
          2,39
          3,7
          4,3
      _images:
      - label: Your Line Graph
        filename: std_ig32a352_plot.png
        part: Check graph is similar to expected graph
      - label: Expected Line Graph
        filename: ref_jjxkzr3s_plot.png
        part: Check graph is similar to expected graph
      _autograder_files:
      - path: /grade/tests/data.csv
        contents: TnVtYmVyIG9mIFRWIFNob3dzLEZyZXF1ZW5jeQowLDkKMSwxNwoyLDM5CjMsNwo0LDMK
      - path: /grade/student/data.csv
        contents: TnVtYmVyIG9mIFRWIFNob3dzLEZyZXF1ZW5jeQowLDkKMSwxNwoyLDM5CjMsNwo0LDMK
---
# {{ params.vars.title }}
{{ params.vars.description }} The results are shown in the table below

<pl-dataframe params-name="df" show-index="false" show-dimensions="false" display-language="r" show-python="false"></pl-dataframe>

<pl-card title="Instructions">

Please open the RStudio workspace below and edit the `student.R` script to complete the following task:

Please write R code that generates a line graph with the following properties:

- The title of the line graph should be '{{ params.vars.graph_title }}'.
- The x-axis label should be '{{ params.vars.x_axis }}'.
- The y-axis label should be '{{ params.vars.y_axis }}'.
- The graph style {{ params.vars.overplotted }} be overplotted.
- The color of the line graph should be {{ params.vars.color }}.

When you are ready to test your code, click the "Grade" button.

Note: You should not need to use `ggplot2` for this question, and you are not advised to do so, as it may interfere with the autograder.

Once you are satisfied with the plot your code generates, make sure the script file is saved in RStudio.

To submit your answer after saving it in RStudio, come back to this page and select "Save & Grade" or "Save only" at the bottom of the page.

</pl-card>

## Part 1

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)