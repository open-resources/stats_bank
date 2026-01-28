---
title: Proportion who feel the president is doing an acceptable job
topic: Foundations for inference
author: Christina Yang
source: 8.3
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.6
- 5.1.1.7
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
- CY
assets: null
part1:
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 1
    blank: true
part2:
  type: symbolic-input
  pl-customizations:
    label: $P^{'} \sim $
    variables: p, q
    weight: 1
    allow-blank: false
    custom_functions: N
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
    fixed-order: true
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $EBM=$
myst:
  substitutions:
    params:
      vars:
        title: Proportion who feel the president is doing an acceptable job
      p: 0.67
      graph_z_score: 1.645
      sample_size: 1474
      p_yes: 67
      c_level: 99
      part1:
        option1:
          value: The total number of people surveyed
        option2:
          value: The difference between the proportion of people who feel the president
            is doing an acceptable job and those who do not
        option3:
          value: The number of people who do not feel that the president is doing
            an acceptable job.
        statement1:
          value: X
          matches: The number of people who feel that the president is doing an acceptable
            job.
        statement2:
          value: P'
          matches: The proportion of people in a sample who feel that the president
            is doing an acceptable job.
      standard_error: 0.01224744871391589
      part3:
        ans1:
          value: 'Yes'
          feedback: Try again please!
        ans2:
          value: 'No'
          feedback: Correct!
---
# {{ params.vars.title }}
According to a recent survey of {{ params.sample_size }} people, {{ params.p_yes }}% feel that the president is doing an acceptable job. We are interested in the population proportion of people who feel the president is doing an acceptable job.

## Part 1

Match the random variables X and P' to the right definition

### Answer Section

## Part 2

Define the distribution should you use for this problem, e.g. U(1,3).

### Answer Section

$$P^{'} \sim N\left({{ params.p }}, \sqrt{\frac{({{ params.p }})\*(1 - {{ params.p }})}{ {{ params.sample_size }} }}\right)$$

## Part 3

Is the following graph a proper representation of the {{ params.c_level }}% confidence interval?
<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}

## Part 4

What should the error bound be for the confidence interval with {{ params.c_level }}% confidence level?

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)