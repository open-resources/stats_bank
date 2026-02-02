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
    params:
      vars:
        title: Repeated water samples
      text_part5:
        budget: reduced
        only: 'only '
        can: 'can '
      part3:
        num1: 5
      part5:
        num1: 268
        num2: 900
        num3: 822
        ans1:
          value: It is impossible to predict the variability of the new distribution.
          feedback: The distribution will tend to be more variable when we have fewer
            observations per sample.
        ans2:
          value: The variability of the new distribution will be the same as the original.
          feedback: The distribution will tend to be more variable when we have fewer
            observations per sample.
        ans3:
          value: The variability of the new distribution will be less than the original.
          feedback: The distribution will tend to be more variable when we have fewer
            observations per sample.
        ans4:
          value: The variability of the new distribution will be greater than the
            original.
          feedback: The distribution will tend to be more variable when we have fewer
            observations per sample.
      description:
        num1: 5
        num2: 30
        num3: 822
        num4: 900
      part1:
        ans1:
          value: Normal Distribution
          feedback: Try again please!
        ans2:
          value: Poisson Distribution
          feedback: Try again please!
        ans3:
          value: Binomial Distribution
          feedback: Try again please!
        ans4:
          value: Sampling Distribution
          feedback: Correct!
      part2:
        ans1:
          value: Symmetric, because the sample size is large and the expected population
            proportion is within the range of 5-30%, satisfying the success-failure
            condition.
          feedback: Correct!
        ans2:
          value: Right-skewed, because the expected proportion of success is lower
            than the proportion of failure.
          feedback: Try again please!
        ans3:
          value: Left-skewed, because the expected proportion of success is higher
            than the proportion of failure.
          feedback: Try again please!
        ans4:
          value: It is not possible to determine the shape of the distribution from
            the information given.
          feedback: Try again please!
      part4:
        ans1:
          value: Margin of error
          feedback: Try again please!
        ans2:
          value: Standard deviation
          feedback: Try again please!
        ans3:
          value: Standard error
          feedback: Correct!
        ans4:
          value: Sample mean
          feedback: Try again please!
---
# {{ params.vars.title }}
A nonprofit wants to understand the fraction of households that have elevated levels of lead in their drinking water.

They expect at least ${{ params.description.num1 }}$% of homes will have elevated levels of lead, but not more than about ${{ params.description.num2 }}$%.

They randomly sample ${{ params.description.num3 }}$ homes and work with the owners to retrieve water samples, and they compute the fraction of these homes with elevated lead levels.

They repeat this ${{ params.description.num4}}$ times and build a distribution of sample proportions.

## Part 1

What is this distribution called?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Would you expect the shape of this distribution to be symmetric, right skewed, or left skewed? Choose appropriate reasoning.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

If the proportions are distributed around ${{ params.part3.num1 }}$%, what is the variability of the distribution? Please provide your answer to four decimal places.

### Answer Section

Please enter a numeric value in.

## Part 4

What is the formal name of the value you computed in part 3?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

Suppose the researchers' budget is {{ params.text_part5.budget }}, and they are {{ params.text_part5.only }}able to collect ${{ params.part5.num1 }}$ observations per sample, but they {{ params.text_part5.can }}still collect ${{ params.part5.num2 }}$ samples.

They build a new distribution of sample proportions.

How will the variability of this new distribution compare to the variability of the distribution when each sample contained ${{ params.part5.num3 }}$ observations?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)