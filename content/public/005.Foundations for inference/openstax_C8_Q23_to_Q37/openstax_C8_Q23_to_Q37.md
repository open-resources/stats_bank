---
title: Foothill College Student Age
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
    digits: 1
    allow-blank: false
    label: $\bar{x} = $
part2:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $n = $
part3:
  type: symbolic-input
  pl-customizations:
    allow-blank: false
    variables: sigma, mu, n, x_bar, s, x
    allow-trig-functions: false
    allow-complex: false
    suffix: $ = {{ params.sigma }}$
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: symbolic-input
  pl-customizations:
    allow-blank: false
    variables: sigma, mu, n, x_bar, s, x
    allow-trig-functions: false
    allow-complex: false
    label: $\bar{x}\sim$
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part7:
  type: symbolic-input
  pl-customizations:
    label: $X\sim$
    custom_functions: N, B, X, F, T
    allow-trig-functions: false
    allow-complex: false
    variables: mu, sigma, p, q
    weight: 1
    allow-blank: false
part8:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    allow-blank: false
    label: $\alpha = $
part9:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    allow-blank: false
    label: $\frac{\alpha}{2} = $
part10:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    allow-blank: false
    label: $\text{EBM} = $
part11:
  type: matrix-component-input
  pl-customizations:
    comparison: decdig
    digits: 2
    allow-blank: false
    allow-fractions: false
    allow-partial-credit: true
    label: $CI_{ {{ params.confidence }}\% } = $
part12:
  type: matching
  pl-customizations:
    weight: 1
    blank: true
    counter-type: decimal
    none-of-the-above: true
part13:
  type: multiple-choice
  pl-customizations:
    weight: 1
part14:
  type: multiple-choice
  pl-customizations:
    weight: 1
part15:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Foothill College Student Age
    params_x_bar: 30.0
    params_sigma: 15.2
    params_sample_size: 22
    params_alpha: 0.1
    params_alpha_one_tail: 0.05
    params_confidence: 90
    params_z_score: 1.645
    params_ebm: 5.330870711755683
    params_fake_sample_size: 66
    params_fake_confidence: 95
    params_part4_ans1_value: The mean age of a sample of 22 Foothill College Students
    params_part4_ans1_feedback: Nice work!
    params_part4_ans2_value: The most frequent age of a sample of 22 Foothill College
      Students
    params_part4_ans2_feedback: Please try again
    params_part4_ans3_value: The mean age of all Foothill College Students
    params_part4_ans3_feedback: Please try again!
    params_part4_ans4_value: The mean age of a Foothill College Students
    params_part4_ans4_feedback: Please try again!
    params_part6_ans1_value: 'Yes'
    params_part6_ans1_feedback: Nice work!
    params_part6_ans2_value: 'No'
    params_part6_ans2_feedback: Please try again
    params_part11_CI: null
    params_part12_option1_name: alpha-correct
    params_part12_option1_value: $\frac{\alpha}{2} = 0.05$
    params_part12_option2_value: $\alpha = 0.1$
    params_part12_option3_value: $\alpha = 0.05$
    params_part12_option4_value: $\frac{\alpha}2 = 0.1$
    params_part12_option5_value: '0.95'
    params_part12_option6_value: 90%
    params_part12_option7_value: '5.33'
    params_part12_statement1_value: a?
    params_part12_statement1_matches: '0.90'
    params_part12_statement2_value: b?
    params_part12_statement2_matches: alpha-correct
    params_part12_statement3_value: c?
    params_part12_statement3_matches: alpha-correct
    params_part12_statement4_value: d?
    params_part12_statement4_matches: '24.67'
    params_part12_statement5_value: e?
    params_part12_statement5_matches: '30.00'
    params_part12_statement6_value: f?
    params_part12_statement6_matches: '35.33'
    params_part13_ans1_value: We are 90% confident that the true mean age for Winter
      Foothill College students is between (lower_bound) and (upper_bound).
    params_part13_ans1_feedback: Nice work!
    params_part13_ans2_value: We are 90% confident that the true mean age for Winter
      Foothill College students is no less than (lower_bound).
    params_part13_ans2_feedback: Please try again!
    params_part13_ans3_value: We are 90% confident that the true mean age for Winter
      Foothill College students is no more than (upper_bound).
    params_part13_ans3_feedback: Please try again!
    params_part13_ans4_value: We are 90% confident that the true mean age for Winter
      Foothill College students is 30.0.
    params_part13_ans4_feedback: Please try again!
    params_part13_ans5_value: The true mean age for Winter Foothill College students
      is between (lower_bound) and (upper_bound).
    params_part13_ans5_feedback: Please try again!
    params_part13_ans6_value: The true mean age for Winter Foothill College students
      is no less than (lower_bound).
    params_part13_ans6_feedback: Please try again!
    params_part13_ans7_value: The true mean age for Winter Foothill College students
      is no more than (upper_bound).
    params_part13_ans7_feedback: Please try again!
    params_part14_ans1_value: The error bound for the mean would decrease because
      as the sample size increases, you need less area under the normal curve (which
      translates into a smaller interval) to capture the true population mean.
    params_part14_ans1_feedback: Nice work!
    params_part14_ans2_value: The error bound for the mean would increase because
      as the sample size decreases, you need more area under the normal curve (which
      translates into a larger interval) to capture the true population mean.
    params_part14_ans2_feedback: Please try again!
    params_part14_ans3_value: The error bound for the mean would decrease because
      as the sample size increases, you need more area under the normal curve (which
      translates into a larger interval) to capture the true population mean.
    params_part14_ans3_feedback: Please try again!
    params_part14_ans4_value: The error bound for the mean would increase because
      as the sample size decreases, you need less area under the normal curve (which
      translates into a smaller interval) to capture the true population mean.
    params_part14_ans4_feedback: Please try again!
    params_part15_ans1_value: The error bound for the mean would decrease because
      as the CL decreases, you need less area under the normal curve (which translates
      into a smaller interval) to capture the true population mean.
    params_part15_ans1_feedback: Please try again!
    params_part15_ans2_value: The error bound for the mean would increase because
      as the CL increases, you need more area under the normal curve (which translates
      into a larger interval) to capture the true population mean.
    params_part15_ans2_feedback: Nice work!
    params_part15_ans3_value: The error bound for the mean would decrease because
      as the CL decreases, you need more area under the normal curve (which translates
      into a larger interval) to capture the true population mean.
    params_part15_ans3_feedback: Please try again!
    params_part15_ans4_value: The error bound for the mean would increase because
      as the CL increases, you need less area under the normal curve (which translates
      into a smaller interval) to capture the true population mean.
    params_part15_ans4_feedback: Please try again!
---
# {{ params_vars_title }}
The mean age for all Foothill College students for a recent Fall term was 33.2. The population standard deviation has been pretty consistent at {{ params_sigma }}. Suppose that {{ params.sample_size }} Winter students were randomly selected. The mean age for the sample was {{ params.x_bar }}. We are interested in the true mean age for Winter Foothill College students. Let $X$ = the age of a Winter Foothill College student.

*For parts 8 through 15, you'll be asked to construct a {{ params_confidence }}% Confidence Interval for the true mean age of Winter Foothill College students by working out then answering the next seven exercises.*

## Part 1

Identify the sample mean

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\bar{x} = {{ params.x_bar }}$

## Part 2

Identify the sample size.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\sigma = {{ params_sigma }}$

## Part 3

What measure is this?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$n = {{ params.sample_size }}$

## Part 4

Identify the correct definition of the random variable $\bar{X}$.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}
- {{ params_part4_ans3_value }}
- {{ params_part4_ans4_value }}

### pl-answer-panel

As the sample size increases, there will be less variability in the mean, so the interval size decreases.

## Part 5

What is $\bar{x}$ estimating?

### Answer Section

### pl-answer-panel

$\bar{x}\sim\mu$

## Part 6

Is $\sigma_x$ known?

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}

### pl-answer-panel

$\sigma_x$ is known.

## Part 7

Based on your answer to part 4, state the exact distribution to use when calculating the confidence interval. (e.g. $N(0,1)$)

### Answer Section

## Part 8

How much area is in both tails (combined)?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\alpha = {{ params_alpha }}$

## Part 9

How much area is in each tail?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\frac{\alpha}{2} = {{ params_alpha_one_tail }}$

## Part 10

Identify the error bound of the confidence interval.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$\text{EBM} = {{ params_ebm }}$

## Part 11

Identify the confidence interval.

### Answer Section

### pl-answer-panel

$\text{CI} = <pl-matrix-latex params-name="part11_CI"></pl-matrix-latex>$

## Part 12

Please match each of the following blanks on the graph with their values.

<pl-figure file-name="figure1.png" type="dynamic" width="600px"></pl-figure>

### Answer Section

## Part 13

Which of the following correctly explains what the interval means?

### Answer Section

- {{ params_part13_ans1_value }}
- {{ params_part13_ans2_value }}
- {{ params_part13_ans3_value }}
- {{ params_part13_ans4_value }}
- {{ params_part13_ans5_value }}
- {{ params_part13_ans6_value }}
- {{ params_part13_ans7_value }}

## Part 14

Using the same mean, standard deviation, and level of confidence, how would the error bound change if $n$ were {{ params.fake_sample_size }} instead of 25? Why?

### Answer Section

- {{ params_part14_ans1_value }}
- {{ params_part14_ans2_value }}
- {{ params_part14_ans3_value }}
- {{ params_part14_ans4_value }}

## Part 15

Using the same mean, standard deviation, and sample size, how would the error bound change if the confidence level were {{ params.fake_confidence }}% instead of {{ params_confidence }}%? Why?

### Answer Section

- {{ params_part15_ans1_value }}
- {{ params_part15_ans2_value }}
- {{ params_part15_ans3_value }}
- {{ params_part15_ans4_value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)