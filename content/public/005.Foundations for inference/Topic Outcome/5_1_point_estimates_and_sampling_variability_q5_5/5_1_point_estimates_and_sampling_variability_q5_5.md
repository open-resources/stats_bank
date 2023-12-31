---
title: Repeated water samples
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.2
- 5.1.1.5
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
- CR
assets: null
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
    rtol: 5.0e-05
    weight: 1
    allow-blank: true
    label: $variability= $
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Repeated water samples
    params_text_part5_budget: reduced
    params_text_part5_only: 'only '
    params_text_part5_can: 'can '
    params_part3_num1: 10
    params_part5_num1: 259
    params_part5_num2: 989
    params_part5_num3: 823
    params_part5_ans1_value: It is impossible to predict the variability of the new
      distribution.
    params_part5_ans1_feedback: The distribution will tend to be more variable when
      we have fewer observations per sample.
    params_part5_ans2_value: The variability of the new distribution will be the same
      as the original.
    params_part5_ans2_feedback: The distribution will tend to be more variable when
      we have fewer observations per sample.
    params_part5_ans3_value: The variability of the new distribution will be less
      than the original.
    params_part5_ans3_feedback: The distribution will tend to be more variable when
      we have fewer observations per sample.
    params_part5_ans4_value: The variability of the new distribution will be greater
      than the original.
    params_part5_ans4_feedback: The distribution will tend to be more variable when
      we have fewer observations per sample.
    params_description_num1: 5
    params_description_num2: 30
    params_description_num3: 823
    params_description_num4: 989
    params_part1_ans1_value: Normal Distribution
    params_part1_ans1_feedback: Try again please!
    params_part1_ans2_value: Poisson Distribution
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: Binomial Distribution
    params_part1_ans3_feedback: Try again please!
    params_part1_ans4_value: Sampling Distribution
    params_part1_ans4_feedback: Correct!
    params_part2_ans1_value: Symmetric, because the sample size is large and the expected
      population proportion is within the range of 5-30%, satisfying the success-failure
      condition.
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: Right-skewed, because the expected proportion of success
      is lower than the proportion of failure.
    params_part2_ans2_feedback: Try again please!
    params_part2_ans3_value: Left-skewed, because the expected proportion of success
      is higher than the proportion of failure.
    params_part2_ans3_feedback: Try again please!
    params_part2_ans4_value: It is not possible to determine the shape of the distribution
      from the information given.
    params_part2_ans4_feedback: Try again please!
    params_part4_ans1_value: Margin of error
    params_part4_ans1_feedback: Try again please!
    params_part4_ans2_value: Standard deviation
    params_part4_ans2_feedback: Try again please!
    params_part4_ans3_value: Standard error
    params_part4_ans3_feedback: Correct!
    params_part4_ans4_value: Sample mean
    params_part4_ans4_feedback: Try again please!
---
# {{ params_vars_title }}
A nonprofit wants to understand the fraction of households that have elevated levels of lead in their drinking water.

They expect at least ${{ params_description_num1 }}$% of homes will have elevated levels of lead, but not more than about ${{ params_description_num2 }}$%.

They randomly sample ${{ params_description_num3 }}$ homes and work with the owners to retrieve water samples, and they compute the fraction of these homes with elevated lead levels.

They repeat this ${{ params_description_num4}}$ times and build a distribution of sample proportions.

## Part 1

What is this distribution called?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

Sampling distribution

## Part 2

Would you expect the shape of this distribution to be symmetric, right skewed, or left skewed? Choose appropriate reasoning.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}

### pl-answer-panel

If the population proportion is in the 5-30% range, the success-failure condition would be satisfied and the sampling distribution would be symmetric.

## Part 3

If the proportions are distributed around ${{ params_part3_num1 }}$%, what is the variability of the distribution? Please provide your answer to four decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

We use the formula for the standard error:$SE= \sqrt{\frac{p (1 - p)}{n}}= {{correct_answers.part3_ans}}$

## Part 4

What is the formal name of the value you computed in part 3?

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}
- {{ params_part4_ans3_value }}
- {{ params_part4_ans4_value }}

### pl-answer-panel

Standard error

## Part 5

Suppose the researchers' budget is {{ params.text_part5.budget }}, and they are {{ params.text_part5.only }}able to collect ${{ params_part5_num1 }}$ observations per sample, but they {{ params.text_part5.can }}still collect ${{ params_part5_num2 }}$ samples.

They build a new distribution of sample proportions.

How will the variability of this new distribution compare to the variability of the distribution when each sample contained ${{ params_part5_num3 }}$ observations?

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}
- {{ params_part5_ans3_value }}
- {{ params_part5_ans4_value }}

### pl-answer-panel

The distribution will tend to be more variable when we have fewer observations per sample.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)