---
title: Study abroad
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.3
- 6.1.1.5
- 6.1.1.6
- 6.1.1.7
- 6.1.1.8
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
- AB
assets:
- sample.html
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Lower Limit = '
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Upper Limit = '
    suffix: ''
part4:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer1.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Study abroad
    params_vars_n: 1212
    params_vars_p: 51.0
    params_vars_confidence_level: 98.0
    params_vars_lower_bound: 0.4766
    params_vars_lower_bound_percent: 48
    params_vars_upper_bound: 0.5434
    params_vars_upper_bound_percent: 54
    params_part1_ans1_value: Yes. The sample is a perfect representation of all high
      school seniors.
    params_part1_ans1_feedback: Incorrect.
    params_part1_ans2_value: Yes. The sample is a perfect representation of all students
      who took the SAT.
    params_part1_ans2_feedback: Incorrect.
    params_part1_ans3_value: No. The sample only represents students who completed
      the web survey.
    params_part1_ans3_feedback: Incorrect.
    params_part1_ans4_value: No. The sample only represents students who took the
      SAT, and this was also an online survey.
    params_part1_ans4_feedback: Correct!
    params_part5_ans1_value: 98% confidence means that if we repeated this survey
      100 times, 98 of the results would fall within this interval.
    params_part5_ans1_feedback: Incorrect.
    params_part5_ans2_value: 98% confidence means that we are 98% certain that the
      true proportion is within this interval.
    params_part5_ans2_feedback: Incorrect.
    params_part5_ans3_value: 98% confidence means that 98% of the time the true proportion
      will fall within this interval.
    params_part5_ans3_feedback: Incorrect.
    params_part5_ans4_value: 98% of such random samples would produce a 98% confidence
      interval that includes the true proportion.
    params_part5_ans4_feedback: Correct!
    params_part6_ans1_value: No. The interval lies entirely above 50%.
    params_part6_ans1_feedback: Incorrect.
    params_part6_ans2_value: Yes. The interval lies entirely below 50%.
    params_part6_ans2_feedback: Incorrect.
    params_part6_ans3_value: No. The interval lies entirely below 50%.
    params_part6_ans3_feedback: Incorrect.
    params_part6_ans4_value: Yes. The interval lies entirely above 50%.
    params_part6_ans4_feedback: Correct!
---
# {{ params_vars_title }}
A survey on {{  params_vars_n }} high school seniors who took the SAT and who completed an optional web survey shows that {{ params_vars_p }}% of high school seniors are fairly certain that they will participate in a study abroad program in college.

## Part 1

Is this sample a representative sample from the population of all high school seniors in the US? Yes or No?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Part 2: (a)

Let's suppose the conditions for inference are met. Even if your answer to Part 1 indicated that this approach would not be reliable, this analysis may still be interesting to carry out (though not report). Calculate the lower bound of a {{ params.vars.confidence_level }}% confidence interval for the proportion of high school seniors (of those who took the SAT) who are fairly certain they will participate in a study abroad program in college, and interpret this interval in context.

### Answer Section

Please enter in a numeric value.

## Part 2: (b)

Calculate the upper bound of a {{ params.vars.confidence_level }}% confidence interval for the proportion of high school seniors (of those who took the SAT) who are fairly certain they will participate in a study abroad program in college.

### Answer Section

Please enter in a numeric value.

## Part 2: (c)

In one sentence interpret this interval in context.

### Answer Section

Please enter in a text response.

### pl-answer-panel

$({{ params.vars.lower_bound }}, {{ params.vars.upper_bound }})$. We are ${{ params.vars.confidence_level }}$% confident that ${{ params.vars.lower_bound_percent }}$% to ${{ params.vars.upper_bound_percent }}$% of high school seniors who took the SAT are fairly certain that they will participate in a study abroad program in college.

## Part 3

What does "{{ params.vars.confidence_level }}% confidence" mean?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}
- {{ params_part5_ans3_value }}
- {{ params_part5_ans4_value }}

## Part 4

Based on this interval, would it be appropriate to claim that the majority of high school seniors are fairly certain that they will participate in a study abroad program in college? Yes or No?

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}
- {{ params_part6_ans3_value }}
- {{ params_part6_ans4_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)