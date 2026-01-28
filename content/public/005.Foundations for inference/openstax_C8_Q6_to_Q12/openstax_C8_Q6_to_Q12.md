---
title: Census Form Length
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: 8.1
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.4
- 5.1.1.6
- 5.1.1.7
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
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    allow-blank: false
    label: $\bar{x} = $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    allow-blank: false
    label: $\sigma = $
part3:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n = $
part4:
  type: symbolic-input
  pl-customizations:
    label: $X\sim$
    custom_functions: N,B
    variables: mu,sigma
    allow-trig-functions: false
    weight: 1
    allow-blank: false
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\text{EBM} = $
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
part8:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n_{CL={{params.higher_confidence}}\%} = $
myst:
  substitutions:
    params:
      vars:
        title: Census Form Length
      x_bar: 8.1
      sigma: 1.7
      sample_size: 225
      other_sample_size: 75
      alpha: 0.1
      confidence: 90
      z_score: 1.645
      graph_z_score: 1.645
      higher_confidence: 99
      higher_z_score: 2.58
      part5:
        ans1:
          value: 'Yes'
          feedback: Correct!
        ans2:
          value: 'No'
          feedback: Try again please!
      part7:
        ans1:
          value: The level of confidence would decrease because decreasing $n$ makes
            the confidence interval wider, so at the same error bound, the confidence
            level decreases.
          feedback: Correct!
        ans2:
          value: The level of confidence would increase because increasing $n$ makes
            the confidence interval smaller, so at the same error bound, the confidence
            level increases.
          feedback: Try again please!
        ans3:
          value: The level of confidence would increase because decreasing $n$ makes
            the confidence interval smaller, so at the same error bound, the confidence
            level increases.
          feedback: Try again please!
        ans4:
          value: The level of confidence would decrease because increasing $n$ makes
            the confidence interval wider, so at the same error bound, the confidence
            level decreases.
          feedback: Try again please!
---
# {{ params.vars.title }}
The U.S. Census Bureau conducts a study to determine the time needed to complete the short form. The Bureau surveys {{ params.sample_size }} people. The sample mean is {{ params.x_bar }} minutes. There is a known standard deviation of {{ params.sigma }} minutes. The population distribution is assumed to be normal.

## Part 1

Identify the sample mean

### Answer Section

Please enter a numeric value in.

## Part 2

Identify the standard deviation

### Answer Section

Please enter a numeric value in.

## Part 3

Identify the sample size

### Answer Section

Please enter a numeric value in.

## Part 4

Please define the distribution that should be used. (Ex. $exp(1)$, $N(0,1)$, $B(5, 0.5)$)

### Answer Section

## Part 5

Is the following graph a proper representation of the {{ params.confidence }}% confidence interval?

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Part 6

What should the error bound be for the confidence interval with {{ params.confidence }}% confidence level?

### Answer Section

Please enter a numeric value in.

## Part 7

If the Census did another survey, kept the error bound the same, and surveyed {{ params.other_sample_size }} people instead of 200, what would happen to the level of confidence? Why?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Part 8

Suppose the Census needed to be {{ params.higher_confidence }}% confident of the population mean length of time. Without changing the error bound from part 6, how many people would need to be surveyed?

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)