---
title: Offshore drilling, Part I
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.1
- 6.1.1.4
- 6.1.1.5
- 6.1.1.6
- 6.1.1.8
- 6.1.1.20
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
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    rtol: 0.1
    weight: 1
    allow-blank: true
    label: 'College grads:'
    suffix: '%'
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    rtol: 0.1
    weight: 1
    allow-blank: true
    label: 'Non-college grads:'
    suffix: '%'
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    rtol: 0.01
    weight: 1
    allow-blank: true
    label: $\hat{p}=$
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    rtol: 0.05
    weight: 1
    allow-blank: true
    label: $Z=$
part8:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    rtol: 0.001
    weight: 1
    allow-blank: true
    label: p-value =
part9:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Offshore drilling, Part I
      part3:
        ans1:
          value: '$H_0: p_{CG} = p_{NCG}$, $H_A: p_{CG} ≠ p_{NCG}$'
          feedback: Correct!
        ans2:
          value: '$H_0: p_{CG} = p_{NCG}$, $H_A: p_{CG} > p_{NCG}$'
          feedback: Incorrect!
        ans3:
          value: '$H_0: p_{CG} = p_{NCG}$, $H_A: p_{CG} < p_{NCG}$'
          feedback: Incorrect!
        ans4:
          value: '$H_0: p_{CG} > p_{NCG}$, $H_A: p_{CG} ≠ p_{NCG}$'
          feedback: Incorrect!
      part4:
        ans1:
          value: 'Yes'
          feedback: Correct! It is a random sample.
        ans2:
          value: 'No'
          feedback: Incorrect!
      part6:
        ans1:
          value: 'Yes'
          feedback: Correct!
        ans2:
          value: 'No'
          feedback: Incorrect!
      part9:
        ans1:
          value: Since the p-value is very large, we reject $H_0$. The data provide
            weak evidence that the proportion of college graduates who do not have
            an opinion on this issue is different than that of non-college graduates.
          feedback: Try again please!
        ans2:
          value: Since the p-value is very small, we accept $H_0$. The data provide
            strong evidence that the proportion of college graduates who do not have
            an opinion on this issue is the same as that of non-college graduates.
          feedback: Try again please!
        ans3:
          value: Since the p-value is very small, we reject $H_0$. The data provide
            strong evidence that the proportion of college graduates who do not have
            an opinion on this issue is different than that of non-college graduates.
          feedback: Correct!
        ans4:
          value: Since the p-value > 0.05, we fail to reject $H_0$. The data do not
            provide strong evidence that the proportion of college graduates who do
            not have an opinion on this issue is different from that of non-college
            graduates.
          feedback: Try again please!
      yes_support: 153
      yes_oppose: 186
      yes_do_not_know: 104
      yes_total: 443
      no_support: 139
      no_oppose: 117
      no_do_not_know: 131
      no_total: 387
      total: 830
---
# {{ params.vars.title }}
A survey asked {{ params.total }} randomly sampled registered voters in California "Do you support? Or do you oppose? Drilling for oil and natural gas off the Coast of California? Or do you not know enough to say?" Below is the distribution of responses, separated based on whether or not the respondent graduated from college.

| | **College Grad** | |
|-----------------|------------------------------|------------------------------|
| | **Yes** | **No** |
|-----------------|------------------------------|------------------------------|
| **Support** | {{ params.yes_support }}| {{ params.no_support }} |
| **Oppose** | {{ params.yes_oppose }} | {{ params.no_oppose }} |
| **Do not know** | {{ params.yes_do_not_know }} | {{ params.no_do_not_know }} |
|-----------------|------------------------------|-----------------------------|
| **Total** | {{ params.yes_total }} | {{ params.no_total }} |

## Part 1

What percent of college graduates in this sample do not know enough to have an opinion on drilling for oil and natural gas off the Coast of California?

### Answer Section

Enter in a numeric value

## Part 2

What percent of non-college graduates in this sample do not know enough to have an opinion on drilling for oil and natural gas off the Coast of California?

### Answer Section

Enter in a numeric value

## Part 3

Let $p\_{CG}$ and $p\_{NCG}$ represent the proportion of college graduates and non-college graduates who responded "do not know". Formulate the null and alternative hypothesis.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

Is the independence condition being satisfied?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Part 5

Calculate the pooled proportion.

### Answer Section

Enter in a numeric value

## Part 6

Considering the pooled proportion, has the success-failure condition been satisfied?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Part 7

Calculate the test statistic.

### Answer Section

Enter in a numeric value

## Part 8

Determine the p-value from the calculated test statistic.

### Answer Section

Enter in a numeric value

## Part 9

Based on the p-value and a significance level of 0.05, state whether you will reject or fail to reject the null hypothesis and explain the conclusion.

### Answer Section

- {{ params.part9.ans1.value }}
- {{ params.part9.ans2.value }}
- {{ params.part9.ans3.value }}
- {{ params.part9.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)