---
title: Tranquilizer effect time
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: 8.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.0
- 7.1.1.4
- 7.1.1.5
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
- GKF
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: false
    label: $\bar{x}=$
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: false
    label: $s_x=$
part3:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n=$
part4:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $df=$
part5:
  type: matching
  showCorrectAnswer: true
  pl-customizations:
    weight: 1
    blank: true
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: matrix-component-input
  pl-customizations:
    comparison: decdig
    digits: 5
    weight: 1
    allow-blank: false
    label: $\text{CI}=$
part8:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $\text{EBM}=$
part9:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Tranquilizer effect time
      effect_times:
      - 2.7
      - 2.2
      - 2.7
      - 2.7
      - 2.9
      - 2.8
      confidence_level: 99
      part5:
        option0:
          value: The mean effective length of time of tranquilizers.
        option1:
          value: The variance in effective length of time of tranquilizers.
        statement1:
          value: $X$
          matches: The effective length of time for a tranquilizer.
        statement2:
          value: $\bar{X}$
          matches: The mean effective length of time of tranquilizers from a sample
            of 6 patients.
      part6:
        ans1:
          value: We need to use a Student's-t distribution, because we do not know
            the population standard deviation.
          feedback: Good job!
        ans2:
          value: We need to use a Student's-t distribution, because we know the population
            standard deviation.
          feedback: Try again please!
        ans3:
          value: We need to use a Normal distribution, because we do not know the
            population standard deviation.
          feedback: Try again please!
        ans4:
          value: We need to use a Normal distribution, because we know the population
            standard deviation.
          feedback: Try again please!
      part9:
        ans1:
          value: If we were to sample many groups of nine patients, 99% of the samples
            would contain the true population mean length of time.
          feedback: Good job!
        ans2:
          value: If we were to sample many groups of nine patients, 99% of the samples
            would contain this sample's mean length of time.
          feedback: Try again please!
        ans3:
          value: There is a 99% likelihood that this sample contains the true population
            mean length of time.
          feedback: Try again please!
        ans4:
          value: There is a 99% likelihood that this sample's mean is the true population
            mean length of time.
          feedback: Try again please!
---
# {{ params.vars.title }}
A pharmaceutical company makes tranquilizers. It is assumed that the distribution for the length of time they last is approximately normal. Researchers in a hospital used the drug on a random sample of nine patients. The effective period of the tranquilizer for each patient (in hours) was as follows:

$${{ params.effect_times }}$$

## Part 1

Identify $\bar{x}$.

### Answer Section

Please enter a numeric value in.

## Part 2

Identify $s_x$.

### Answer Section

Please enter a numeric value in.

## Part 3

Identify the sample size.

### Answer Section

Please enter a numeric value in.

## Part 4

Identify the degrees of freedom.

### Answer Section

Please enter a numeric value in.

## Part 5

Match the random variables $X$ and $\bar{X}$ to their definitions.

### Answer Section

## Part 6

Which of the following correctly identifies the distribution should you use for this problem, and correctly explains why?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Part 7

Calculate a {{ params.confidence_level }}% confidence interval.

### Answer Section

## Part 8

Calculate the error bound for the confidence interval calculated in part 7.

### Answer Section

Please enter a numeric value in.

## Part 9

What does it mean to be "{{ params.confidence_level }}% confident" in this problem?

### Answer Section

- {{ params.part9.ans1.value }}
- {{ params.part9.ans2.value }}
- {{ params.part9.ans3.value }}
- {{ params.part9.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)