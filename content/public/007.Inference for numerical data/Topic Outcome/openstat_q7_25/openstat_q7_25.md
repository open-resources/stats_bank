---
title: Friday the 13th, Part II
topic: Inference for numerical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.0
- 7.1.1.7
- 7.1.1.8
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    rtol: 0.01
    digits: 2
    weight: 1
    allow-blank: true
    label: $T= $
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    rtol: 0.001
    digits: 3
    weight: 1
    allow-blank: true
    label: p-value =
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    rtol: 0.01
    digits: 2
    weight: 1
    allow-blank: true
    label: Lower bound =
part6:
  type: number-input
  pl-customizations:
    comparison: decdig
    rtol: 0.01
    digits: 2
    weight: 1
    allow-blank: true
    label: Upper bound =
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Friday the 13th, Part II
    params_part1_ans1_value: '$H_0 : μ_{6^{th}} = μ_{13^{th}}$. $H_A : μ_{6^{th}}
      > μ_{13^{th}}$'
    params_part1_ans1_feedback: Incorrect!
    params_part1_ans2_value: ' $H_0 : μ_{diff} = 0$. $H_A : μ_{diff} ≠ 0$'
    params_part1_ans2_feedback: Correct!
    params_part1_ans3_value: ' $H_0 : μ_{diff} > 0$. $H_A : μ_{diff} ≤ 0$'
    params_part1_ans3_feedback: Incorrect!
    params_part1_ans4_value: '$H_0 : μ_{6^{th}} = μ_{13^{th}}$. $H_A : μ_{6^{th}}
      = μ_{13^{th}}$'
    params_part1_ans4_feedback: Incorrect!
    params_part4_ans1_value: The data suggest that there is no significant difference
      in the average number of traffic accident-related emergency room admissions
      between Friday the $6^{th}$ and Friday the $13^{th}$.
    params_part4_ans1_feedback: Correct!
    params_part4_ans2_value: The data provide strong evidence that the average number
      of traffic accident related emergency room admissions are different between
      Friday the $6^{th}$ and Friday the $13^{th}$.
    params_part4_ans2_feedback: Incorrect!
    params_part4_ans3_value: The results confirm with $100$% certainty that there
      are more accidents on Friday the $6^{th}$ compared to Friday the $13^{th}$.
    params_part4_ans3_feedback: Incorrect!
    params_part4_ans4_value: The data indicate that the number of accidents on Friday
      the $13^{th}$ is significantly higher, proving the superstition about the day
      being unlucky.
    params_part4_ans4_feedback: Incorrect!
    params_part7_ans1_value: Observational studies do not imply causation, and the
      difference observed does not necessarily mean increased risk for a responsible
      adult going out on Friday the $13^{th}$.
    params_part7_ans1_feedback: Correct!
    params_part7_ans2_value: The study conclusively proves that Friday the $13^{th}$
      is an unlucky day with a consistent $52$% increase in the risk of transport
      accident-related hospital admissions.
    params_part7_ans2_feedback: Incorrect!
    params_part7_ans3_value: Scientific evidence from the study confirms that staying
      at home on Friday the $13^{th}$ will reduce the risk of transport accident-related
      hospital admissions.
    params_part7_ans3_feedback: Incorrect!
    params_part7_ans4_value: Observational studies like this one are not capable of
      providing any reliable information about risks, so the study's conclusion is
      not true.
    params_part7_ans4_feedback: Incorrect!
    params_x_bar_6th: 13.32
    params_x_bar_13th: 13.88
    params_x_bar_D: -0.56
    params_s_6th: 2.3
    params_s_13th: 4.53
    params_s_D: 4.77
    params_n: 8
    params_table: |-
      <table style="width:550px">
      <tr>
      <th></th>
      <th>6th</th>
      <th>13th</th>
      <th>diff</th>
      </tr><tr>
      <th>Mean</th>
      <td>$13.32$</td>
      <td>$13.88$</td>
      <td>$-0.56$</td>
      </tr><tr>
      <th>SD</th>
      <td>$2.3$</td>
      <td>$4.53$</td>
      <td>$4.77$</td>
      </tr><tr>
      <th>n</th>
      <td>$8$</td>
      <td>$8$</td>
      <td>$8$</td>
      </tr>
      </table>
---
# {{ params_vars_title }}
In the early 1990's, researchers in the UK collected data on traffic flow, number of shoppers, and traffic accident related emergency room admissions on Friday the $13^{th}$ and the previous Friday, Friday the $6^{th}$. The distributions of data on traffic accident related emergency room admissions from Friday the $6^{th}$ and Friday the $13^{th}$ are shown below for six such paired dates along with summary statistics. You may assume that conditions for inference are met.

{{{ params_table }}}

## Part 1

What are the hypotheses to evaluate if there is a difference between the average numbers of traffic accident related emergency room admissions between Friday the $6^{th}$ and Friday the $13^{th}$?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Part 2

Calculate the test statistic.

### Answer Section

Please enter a numeric value in.

## Part 3

Calculate the p-value.

### Answer Section

Please enter a numeric value in.

## Part 4

What is the conclusion of the hypothesis test?

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}
- {{ params_part4_ans3_value }}
- {{ params_part4_ans4_value }}

## Part 5

Calculate the lower bound of a $95$% confidence interval for the difference between the average numbers of traffic accident related emergency room admissions between Friday the $6^{th}$ and Friday the $13^{th}$.

### Answer Section

Please enter a numeric value in.

## Part 6

Calculate the upper bound bound of a $95$% confidence interval for the difference between the average numbers of traffic accident related emergency room admissions between Friday the $6^{th}$ and Friday the $13^{th}$.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

(-6.49, -0.17)

## Part 7

The conclusion of the original study states, "Friday $13^{th}$ is unlucky for some. The risk of hospital admission as a result of a transport accident may be increased by as much as $52$%. Staying at home is recommended." Do you agree with this statement? Explain your reasoning.

### Answer Section

- {{ params_part7_ans1_value }}
- {{ params_part7_ans2_value }}

### pl-answer-panel

This is an observational study, not an experiment, so we cannot so easily infer a causal intervention implied by this statement. It is true that there is a difference. However, for example, this does not mean that a responsible adult going out on Friday the $13^{th}$ has a higher chance of harm than on any other night

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)