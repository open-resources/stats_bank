---
title: Taste test
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- undefined
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $Z=$
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: true
    label: p-value=
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer1.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
myst:
  substitutions:
    params_vars_title: Taste Test
    params_vars_sample: 76
    params_vars_p_value: 1.3071845366807722e-05
    params_part1_ans1_value: '$H_0: p = 0.75$, $H_A: p ≠ 0.5$'
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: '$H_0: p = 0.75$, $H_A: p = 0.5$'
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: '$H_0: p = 0.5$, $H_A: p ≠ 0.5$'
    params_part1_ans3_feedback: Correct!
    params_part1_ans4_value: '$H_0: p ≠ 0.5$, $H_A: p = 0.5$'
    params_part1_ans4_feedback: Try again please!
    params_part2_ans1_value: Since this is a random sample, independence is satisfied.
      The success-failure condition is also satisfied as we (using $p_0 = 0.5$, we
      expect 38 successes and 38 failures).
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: Since this is a random sample, independence is satisfied.
      The success-failure condition is not satisfied, as our expectation of 38 successes
      and 38 failures, using $p_0 = 0.5$, is not met.
    params_part2_ans2_feedback: Try again please!
    params_part2_ans3_value: Given this is not a random sample, independence is not
      satisfied. The success-failure condition is also satisfied as we (using $p_0
      = 0.5$, we expect 38 successes and 38 failures).
    params_part2_ans3_feedback: Try again please!
    params_part5_ans1_value: Since the p-value $< 0.05$, we reject the null hypothesis.
      Since we rejected $H_0$ and the point estimate suggests people are better than
      random guessing, we can conclude the rate of correctly identifying a soda for
      these people is significantly better than just by random guessing.
    params_part5_ans1_feedback: Correct!
    params_part5_ans2_value: Since the p-value $≥ 0.05$, we fail to reject the null
      hypothesis. Since we did not reject $H_0$ and the point estimate suggests people
      are not better than random guessing, we cannot conclude that the rate of correctly
      identifying a soda for these people is significantly better than just by random
      guessing.
    params_part5_ans2_feedback: Try again please!
---
# {{ params_vars_title }}
Some people claim that they can tell the difference between a diet soda and a regular soda in the first sip. A researcher wanting to test this claim randomly sampled {{ params_vars_sample }} such people. He then filled {{ params_vars_sample }} plain white cups with soda, half diet and half regular through random assignment, and asked each person to take one sip from their cup and identify the soda as diet or regular. {{ params.vars.num_correct_identifications }} participants correctly identified the soda. Do these data provide strong evidence that these people are any better or worse than random guessing at telling the difference between diet and regular soda? Yes or No?

## Part 1

State the null and alternative hypotheses for the taste test.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Part 2

Do the criteria for independence and the success-failure condition hold true?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params.part2.ans4.value }}

## Part 3

Calculate the test statistic.

### Answer Section

Please enter in a numeric value.

## Part 4

Determine the p-value from the calculated test statistic.

### Answer Section

Please enter in a numeric value.

## Part 5

Based on the p-value and a significance level of 0.05, state whether you will reject or fail to reject the null hypothesis and explain the conclusion.

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}

## Part 6

Interpret the p-value in this context.

### Answer Section

Please enter in a text response.

### pl-answer-panel

If in fact people cannot tell the difference between diet and regular soda and they were randomly guessing, the probability of getting a random sample of ${{ params_vars_sample }}$ people where ${{ params.vars.num_correct_identifications }}$ or more identify a soda correctly (or ${{ params.vars.num_correct_identifications }}$ or more identify a soda incorrectly) would be ${{ params.vars.p_value }}$.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)