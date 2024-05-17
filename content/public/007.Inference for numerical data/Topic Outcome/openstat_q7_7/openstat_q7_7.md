---
title: Sleep habits of New Yorkers
topic: Inference for numerical data
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.3
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
- CY
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $T= $
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $df= $
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: true
    label: $p= $
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Sleep habits of New Yorkers
    params_confidence_level: 98.0
    params_sleep_hours: 8
    params_description_n: 24
    params_description_sample_mean: 7.48
    params_description_s: 1.47
    params_description_min_val: 4.76
    params_description_max_val: 10.76
    params_description_alpha: 0.01
    params_table1: |-
      <table style="width:400px">
      <tr>
      <th>$n$</th>
      <th>$\bar x$</th>
      <th>$s$</th>
      <th>$min$</th>
      <th>$max$</th>
      </tr><tr>
      <th>$24$</th>
      <td>$7.48$</td>
      <td>$1.47$</td>
      <td>$4.76$</td>
      <td>$10.76$</td>
      </tr>
      </table>
    params_part1_ans1_value: '$H_0: \mu = 8$, $H_a: \mu < 8$'
    params_part1_ans1_feedback: Correct!
    params_part1_ans2_value: '$H_0: \mu < 8$, $H_a: \mu > 8$'
    params_part1_ans2_feedback: Try again please!
    params_part1_ans3_value: '$H_0: \mu > 8$, $H_a: \mu < 8$'
    params_part1_ans3_feedback: Try again please!
    params_part1_ans4_value: '$H_0: \mu = 8$, $H_a: \mu = 8$'
    params_part1_ans4_feedback: Try again please!
    params_part2_ans1_value: The data should be approximately normally distributed
    params_part2_ans1_feedback: Correct!
    params_part2_ans2_value: The data should be obtained through random sampling methods
    params_part2_ans2_feedback: Correct!
    params_part2_ans3_value: Observations within the sample should be independent
      of each other
    params_part2_ans3_feedback: Correct!
    params_part2_ans4_value: The success-failure condition needs to be met
    params_part2_ans4_feedback: Try again please!
    params_part2_ans5_value: The population standard deviation must be known
    params_part2_ans5_feedback: Try again please!
    params_part2_ans6_value: We need more than 30 observations
    params_part2_ans6_feedback: Try again please!
    params_part6_ans1_value: The probability that New Yorkers sleep exactly 8 hours
      per night.
    params_part6_ans1_feedback: Try again please!
    params_part6_ans2_value: The probability that the sample accurately represents
      the entire population of New Yorkers.
    params_part6_ans2_feedback: Try again please!
    params_part6_ans3_value: The probability of observing the obtained sample mean
      7.48 hours if New Yorkers, on average, sleep 8 per night.
    params_part6_ans3_feedback: Correct!
    params_part6_ans4_value: The probability of observing the obtained sample mean
      of 7.48 hours or more extreme, if New Yorkers, on average, sleep 7.48 hours
      per night.
    params_part6_ans4_feedback: Try again please!
    params_part6_ans5_value: The probability of observing the obtained sample mean
      7.48 of hours or more extreme, if New Yorkers, on average, sleep 8 per night.
    params_part6_ans5_feedback: Try again please!
    params_part7_ans1_value: Reject $H_0$
    params_part7_ans1_feedback: Try again please!
    params_part7_ans2_value: Fail to reject $H_0$
    params_part7_ans2_feedback: Correct!
---
# {{ params_vars_title }}
New York is known as "the city that never sleeps". A random sample of ${{ params_description_n }}$ New Yorkers were asked how much sleep they get per night. Statistical summaries of these data are shown below. The point estimate suggests New Yorkers sleep less than the recommended ${{ params.sleep_hours }}$ hours a night on average. Is the result statistically significant? Use $\alpha={{ params_description_alpha }}$.

{{{ params_table1 }}}

## Part 1

Write the hypotheses in symbols.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

$H_0$: $\mu = {{ params.sleep_hours }}$ (New Yorkers sleep ${{ params.sleep_hours }}$ hrs per night on average.)
$H_A$: $\mu \< {{ params.sleep_hours }}$ (New Yorkers sleep less or more than ${{ params.sleep_hours }}$ hrs per night on average.)

## Part 2

Which of the following assumptions are required to conduct the appropriate hypothesis test?

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}
- {{ params_part2_ans5_value }}

### pl-answer-panel

Independence: The sample is random.
The min/max suggest there are no concerning outliers.

## Part 3

Calculate the test statistic, $T$.

### Answer Section

## Part 4

Calculate the degrees of freedom, $df$.

### Answer Section

### pl-answer-panel

$df={{ params_description_n }}-1$

## Part 5

Find the p-value.

### Answer Section

### pl-answer-panel

If in fact the true population mean of the amount New Yorkers sleep per night was ${{ params.sleep_hours }}$ hours, the probability of getting a random sample of ${{ params_description_n }}$ New Yorkers where the average amount of sleep is ${{ params_description_sample_mean }}$ hours per night or less is ${{ correct_answers.part4_ans }}$

## Part 6

Interpret the p-value in this context. Drawing a picture may be helpful.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}

## Part 7

What is the conclusion of the hypothesis test?

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}
- {{ params_part6_ans3_value }}
- {{ params_part6_ans4_value }}

<!-- ### pl-answer-panel -->

<!-- Since p-value $>0.05$, fail to reject $H_0$. -->

<!-- The data do not provide strong evidence that
New Yorkers sleep more or less than ${{ params.sleep_hours }}$ hours per night
on average -->

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)