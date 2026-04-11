---
title: Middle Class Incomes
topic: Summarizing Data
author: Larita Kipkeu
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
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
- undefined
randomization:
- undefined
taxonomy:
- undefined
span:
- undefined
length:
- undefined
tags:
- LK
assets: null
workspaceTemplates:
- student.R.mustache
- .Rprofile.mustache
autogradeTestFiles:
- solution.R
- test_01.R
part1:
  type: integer-input
  pl-customizations:
    weight: 1
    suffix: $\%$
part2:
  type: integer-input
  pl-customizations:
    weight: 1
    suffix: $\%$
part3:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
part4:
  type: matrix-component-input
  pl-customizations:
    weight: 1
    allow-fractions: 'false'
    allow-blank: false
    label: ${{params.ordinal_rank}}\text{ percentile} = $
part5:
  type: workspace
  gradingMethod: External
myst:
  substitutions:
    params:
      vars:
        title: Middle Class Incomes
      table: |-
        <table style="width:550px">
        <tr>
        <th>Salary Range</th>
        <th>Frequency</th>
        </tr><tr>
        <th>< 20,000</th>
        <td>$0.01$</td>
        </tr><tr>
        <th>20,000–25,000</th>
        <td>$0.03$</td>
        </tr><tr>
        <th>25,000–30,000</th>
        <td>$0.02$</td>
        </tr><tr>
        <th>30,000–40,000</th>
        <td>$0.41$</td>
        </tr><tr>
        <th>40,000–50,000</th>
        <td>$0.13$</td>
        </tr><tr>
        <th>50,000–75,000</th>
        <td>$0.26$</td>
        </tr><tr>
        <th>75,000–99,999</th>
        <td>$0.02$</td>
        </tr><tr>
        <th>100,000+</th>
        <td>$0.01$</td>
        </tr>
        </table>
      part3:
        ans1:
          value: Not all bars have the same width due to varying salary range intervals.
          feedback: You got it!
        ans2:
          value: Bars should ideally represent the same income range to avoid skewed
            visual representation.
          feedback: You got it!
        ans3:
          value: The '< 20,000' and '100,000+' intervals represent open-ended ranges.
          feedback: You got it!
        ans4:
          value: The '< 20,000' and '100,000+' intervals represent closed-ended ranges.
          feedback: Try again please!
        ans5:
          value: Bars should ideally represent varying income range to avoid skewed
            visual representation.
          feedback: Try again please!
      total_respondents: 558
      respondent_data:
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 75,000–99,999
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 25,000–30,000
      - 40,000–50,000
      - 30,000–40,000
      - 25,000–30,000
      - 50,000–75,000
      - 50,000–75,000
      - 40,000–50,000
      - 25,000–30,000
      - Not Sure
      - 50,000–75,000
      - 40,000–50,000
      - Not Sure
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - Not Sure
      - 50,000–75,000
      - Not Sure
      - 20,000–25,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 100,000+
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 40,000–50,000
      - 25,000–30,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - Not Sure
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 25,000–30,000
      - 40,000–50,000
      - 75,000–99,999
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 40,000–50,000
      - 30,000–40,000
      - Not Sure
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - < 20,000
      - 40,000–50,000
      - Not Sure
      - 40,000–50,000
      - 40,000–50,000
      - 40,000–50,000
      - 20,000–25,000
      - 50,000–75,000
      - 50,000–75,000
      - Not Sure
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 20,000–25,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 20,000–25,000
      - 50,000–75,000
      - 50,000–75,000
      - 25,000–30,000
      - 50,000–75,000
      - 50,000–75,000
      - 40,000–50,000
      - 50,000–75,000
      - Not Sure
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - Not Sure
      - 50,000–75,000
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 75,000–99,999
      - 25,000–30,000
      - 75,000–99,999
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - Not Sure
      - 40,000–50,000
      - 20,000–25,000
      - 30,000–40,000
      - 25,000–30,000
      - 30,000–40,000
      - Not Sure
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - Not Sure
      - 50,000–75,000
      - 75,000–99,999
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - Not Sure
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 20,000–25,000
      - 25,000–30,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 40,000–50,000
      - 50,000–75,000
      - 100,000+
      - 30,000–40,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - Not Sure
      - Not Sure
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - Not Sure
      - < 20,000
      - 50,000–75,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 25,000–30,000
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 75,000–99,999
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 75,000–99,999
      - 30,000–40,000
      - 40,000–50,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      - < 20,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 20,000–25,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 100,000+
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 75,000–99,999
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - 50,000–75,000
      - 75,000–99,999
      - 30,000–40,000
      - Not Sure
      - < 20,000
      - 20,000–25,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 100,000+
      - 50,000–75,000
      - Not Sure
      - 40,000–50,000
      - 40,000–50,000
      - 50,000–75,000
      - 50,000–75,000
      - Not Sure
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 40,000–50,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - < 20,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 100,000+
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 20,000–25,000
      - 20,000–25,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 40,000–50,000
      - 40,000–50,000
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 20,000–25,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 40,000–50,000
      - 20,000–25,000
      - 50,000–75,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 50,000–75,000
      - 20,000–25,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - Not Sure
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - 20,000–25,000
      - 40,000–50,000
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - 40,000–50,000
      - 20,000–25,000
      - 25,000–30,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 75,000–99,999
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 75,000–99,999
      - Not Sure
      - Not Sure
      - 40,000–50,000
      - 20,000–25,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - Not Sure
      - 50,000–75,000
      - 50,000–75,000
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 30,000–40,000
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 30,000–40,000
      - Not Sure
      - 50,000–75,000
      - 30,000–40,000
      - 30,000–40,000
      - 40,000–50,000
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - Not Sure
      - 30,000–40,000
      - 30,000–40,000
      - Not Sure
      - Not Sure
      - 30,000–40,000
      - 50,000–75,000
      - 40,000–50,000
      - 50,000–75,000
      - 30,000–40,000
      ordinal_rank: 31^{st}
      graph_instructions:
      - The plot should have a main title of 'Middle Class Incomes Distribution'.
      - The x-axis should be labeled 'Salary Range'.
      - The y-axis should be labeled 'Frequency'.
      - The bars should be appropriately labelled.
      - The bars should be colored darkgreen.
      - The bars should have a purple border.
      - The bars should have a density of 4.
      - The plot should be vertical.
      autograding:
        col1:
        - < 20,000
        - 20,000–25,000
        - 25,000–30,000
        - 30,000–40,000
        - 40,000–50,000
        - 50,000–75,000
        - 75,000–99,999
        - 100,000+
        x:
        - 5
        - 16
        - 11
        - 228
        - 72
        - 145
        - 11
        - 5
        title: Middle Class Incomes Distribution
        xlab: Salary Range
        ylab: Frequency
        color: darkgreen
        border: purple
        density: 4
        horiz: 'False'
        std_plot: std_3zjtiiaq_plot.png
        ref_plot: ref_wzwpd140_plot.png
      _images:
      - label: Your Bar Plot
        filename: std_3zjtiiaq_plot.png
        part: Check graph is similar to expected graph
      - label: Expected Bar Plot
        filename: ref_wzwpd140_plot.png
        part: Check graph is similar to expected graph
---
# {{ params.vars.title }}
${{ params.total_respondents }}$ adult Americans were asked by telephone poll, "What do you think constitutes a middle-class income?" The results are in the table below. Also, include left endpoint, but not the right endpoint.

{{{ params.table }}}

## Part 1

What percentage of the survey answered "not sure"?

### Answer Section

## Part 2

What percentage think that middle-class is from $25,000$ to $50,000$?

### Answer Section

## Part 3

A histogram of the data is provided below.

<pl-figure file-name="figure1.png" type="dynamic" width="450px"></pl-figure>

Which of the choices below are correct based on your analysis of the histogram.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}
- {{ params.part3.ans5.value }}

## Part 4

Find the range of ${{params.ordinal_rank}}$ percentile from the salary ranges.

### Answer Section

## Part 5

Construct a bar graph of the data

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

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)