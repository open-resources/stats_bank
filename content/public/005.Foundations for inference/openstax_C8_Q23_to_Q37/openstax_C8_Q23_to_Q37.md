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
    params:
      vars:
        title: Foothill College Student Age
      x_bar: 29.1
      sigma: 15.7
      sample_size: 29
      alpha: 0.05
      alpha_one_tail: 0.025
      confidence: 95
      z_score: 1.96
      ebm: 5.71421694638424
      fake_sample_size: 87
      fake_confidence: 90
      part4:
        ans1:
          value: The mean age of a sample of 29 Foothill College Students
          feedback: Nice work!
        ans2:
          value: The most frequent age of a sample of 29 Foothill College Students
          feedback: Please try again
        ans3:
          value: The mean age of all Foothill College Students
          feedback: Please try again!
        ans4:
          value: The mean age of a Foothill College Students
          feedback: Please try again!
      part6:
        ans1:
          value: 'Yes'
          feedback: Nice work!
        ans2:
          value: 'No'
          feedback: Please try again
      part11_CI: null
      part12:
        option1:
          name: alpha-correct
          value: $\frac{\alpha}{2} = 0.025$
        option2:
          value: $\alpha = 0.05$
        option3:
          value: $\alpha = 0.025$
        option4:
          value: $\frac{\alpha}2 = 0.05$
        option5:
          value: '0.97'
        option6:
          value: 95%
        option7:
          value: '5.71'
        statement1:
          value: a?
          matches: '0.95'
        statement2:
          value: b?
          matches: alpha-correct
        statement3:
          value: c?
          matches: alpha-correct
        statement4:
          value: d?
          matches: '23.39'
        statement5:
          value: e?
          matches: '29.10'
        statement6:
          value: f?
          matches: '34.81'
      part13:
        ans1:
          value: We are 95% confident that the true mean age for Winter Foothill College
            students is between (lower_bound) and (upper_bound).
          feedback: Nice work!
        ans2:
          value: We are 95% confident that the true mean age for Winter Foothill College
            students is no less than (lower_bound).
          feedback: Please try again!
        ans3:
          value: We are 95% confident that the true mean age for Winter Foothill College
            students is no more than (upper_bound).
          feedback: Please try again!
        ans4:
          value: We are 95% confident that the true mean age for Winter Foothill College
            students is 29.1.
          feedback: Please try again!
        ans5:
          value: The true mean age for Winter Foothill College students is between
            (lower_bound) and (upper_bound).
          feedback: Please try again!
        ans6:
          value: The true mean age for Winter Foothill College students is no less
            than (lower_bound).
          feedback: Please try again!
        ans7:
          value: The true mean age for Winter Foothill College students is no more
            than (upper_bound).
          feedback: Please try again!
      part14:
        ans1:
          value: The error bound for the mean would decrease because as the sample
            size increases, you need less area under the normal curve (which translates
            into a smaller interval) to capture the true population mean.
          feedback: Nice work!
        ans2:
          value: The error bound for the mean would increase because as the sample
            size decreases, you need more area under the normal curve (which translates
            into a larger interval) to capture the true population mean.
          feedback: Please try again!
        ans3:
          value: The error bound for the mean would decrease because as the sample
            size increases, you need more area under the normal curve (which translates
            into a larger interval) to capture the true population mean.
          feedback: Please try again!
        ans4:
          value: The error bound for the mean would increase because as the sample
            size decreases, you need less area under the normal curve (which translates
            into a smaller interval) to capture the true population mean.
          feedback: Please try again!
      part15:
        ans1:
          value: The error bound for the mean would decrease because as the CL decreases,
            you need less area under the normal curve (which translates into a smaller
            interval) to capture the true population mean.
          feedback: Nice work!
        ans2:
          value: The error bound for the mean would increase because as the CL increases,
            you need more area under the normal curve (which translates into a larger
            interval) to capture the true population mean.
          feedback: Please try again!
        ans3:
          value: The error bound for the mean would decrease because as the CL decreases,
            you need more area under the normal curve (which translates into a larger
            interval) to capture the true population mean.
          feedback: Please try again!
        ans4:
          value: The error bound for the mean would increase because as the CL increases,
            you need less area under the normal curve (which translates into a smaller
            interval) to capture the true population mean.
          feedback: Please try again!
---
# {{ params.vars.title }}
The mean age for all Foothill College students for a recent Fall term was 33.2. The population standard deviation has been pretty consistent at {{ params.sigma }}. Suppose that {{ params.sample_size }} Winter students were randomly selected. The mean age for the sample was {{ params.x_bar }}. We are interested in the true mean age for Winter Foothill College students. Let $X$ = the age of a Winter Foothill College student.

*For parts 8 through 15, you'll be asked to construct a {{ params.confidence }}% Confidence Interval for the true mean age of Winter Foothill College students by working out then answering the next seven exercises.*

## Part 1

Identify the sample mean

### Answer Section

Please enter a numeric value in.

## Part 2

Identify the sample size.

### Answer Section

Please enter a numeric value in.

## Part 3

What measure is this?

### Answer Section

Please enter a numeric value in.

## Part 4

Identify the correct definition of the random variable $\bar{X}$.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

What is $\bar{x}$ estimating?

### Answer Section

## Part 6

Is $\sigma_x$ known?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Part 7

Based on your answer to part 4, state the exact distribution to use when calculating the confidence interval. (e.g. $N(0,1)$)

### Answer Section

## Part 8

How much area is in both tails (combined)?

### Answer Section

Please enter a numeric value in.

## Part 9

How much area is in each tail?

### Answer Section

Please enter a numeric value in.

## Part 10

Identify the error bound of the confidence interval.

### Answer Section

Please enter a numeric value in.

## Part 11

Identify the confidence interval.

### Answer Section

## Part 12

Please match each of the following blanks on the graph with their values.

<pl-figure file-name="figure1.png" type="dynamic" width="600px"></pl-figure>

### Answer Section

## Part 13

Which of the following correctly explains what the interval means?

### Answer Section

- {{ params.part13.ans1.value }}
- {{ params.part13.ans2.value }}
- {{ params.part13.ans3.value }}
- {{ params.part13.ans4.value }}
- {{ params.part13.ans5.value }}
- {{ params.part13.ans6.value }}
- {{ params.part13.ans7.value }}

## Part 14

Using the same mean, standard deviation, and level of confidence, how would the error bound change if $n$ were {{ params.fake_sample_size }} instead of 25? Why?

### Answer Section

- {{ params.part14.ans1.value }}
- {{ params.part14.ans2.value }}
- {{ params.part14.ans3.value }}
- {{ params.part14.ans4.value }}

## Part 15

Using the same mean, standard deviation, and sample size, how would the error bound change if the confidence level were {{ params.fake_confidence }}% instead of {{ params.confidence }}%? Why?

### Answer Section

- {{ params.part15.ans1.value }}
- {{ params.part15.ans2.value }}
- {{ params.part15.ans3.value }}
- {{ params.part15.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)