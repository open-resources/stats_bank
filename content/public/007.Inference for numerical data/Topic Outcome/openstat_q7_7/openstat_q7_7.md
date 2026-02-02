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
    params:
      vars:
        title: Sleep habits of New Yorkers
      confidence_level: 96.0
      sleep_hours: 8
      description:
        n: 34
        sample_mean: 6.42
        s: 1.53
        min_val: 3.02
        max_val: 9.71
        alpha: 0.02
      table1: |-
        <table style="width:400px">
        <tr>
        <th>$n$</th>
        <th>$\bar x$</th>
        <th>$s$</th>
        <th>$min$</th>
        <th>$max$</th>
        </tr><tr>
        <th>$34$</th>
        <td>$6.42$</td>
        <td>$1.53$</td>
        <td>$3.02$</td>
        <td>$9.71$</td>
        </tr>
        </table>
      part1:
        ans1:
          value: '$H_0: \mu = 8$, $H_a: \mu < 8$'
          feedback: Correct!
        ans2:
          value: '$H_0: \mu < 8$, $H_a: \mu > 8$'
          feedback: Try again please!
        ans3:
          value: '$H_0: \mu > 8$, $H_a: \mu < 8$'
          feedback: Try again please!
        ans4:
          value: '$H_0: \mu = 8$, $H_a: \mu = 8$'
          feedback: Try again please!
      part2:
        ans1:
          value: The data should be approximately normally distributed
          feedback: Correct!
        ans2:
          value: The data should be obtained through random sampling methods
          feedback: Correct!
        ans3:
          value: Observations within the sample should be independent of each other
          feedback: Correct!
        ans4:
          value: The success-failure condition needs to be met
          feedback: Try again please!
        ans5:
          value: The population standard deviation must be known
          feedback: Try again please!
        ans6:
          value: We need more than 30 observations
          feedback: Try again please!
      part6:
        ans1:
          value: The probability that New Yorkers sleep exactly 8 hours per night.
          feedback: Try again please!
        ans2:
          value: The probability that the sample accurately represents the entire
            population of New Yorkers.
          feedback: Try again please!
        ans3:
          value: The probability of observing the obtained sample mean 6.42 hours
            if New Yorkers, on average, sleep 8 per night.
          feedback: Correct!
        ans4:
          value: The probability of observing the obtained sample mean of 6.42 hours
            or more extreme, if New Yorkers, on average, sleep 6.42 hours per night.
          feedback: Try again please!
        ans5:
          value: The probability of observing the obtained sample mean 6.42 of hours
            or more extreme, if New Yorkers, on average, sleep 8 per night.
          feedback: Try again please!
      part7:
        ans1:
          value: Reject $H_0$
          feedback: Correct!
        ans2:
          value: Fail to reject $H_0$
          feedback: Try again please!
---
# {{ params.vars.title }}
New York is known as "the city that never sleeps". A random sample of ${{ params.description.n }}$ New Yorkers were asked how much sleep they get per night. Statistical summaries of these data are shown below. The point estimate suggests New Yorkers sleep less than the recommended ${{ params.sleep_hours }}$ hours a night on average. Is the result statistically significant? Use $\alpha={{ params.description.alpha }}$.

{{{ params.table1 }}}

## Part 1

Write the hypotheses in symbols.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Which of the following assumptions are required to conduct the appropriate hypothesis test?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}
- {{ params.part2.ans5.value }}

## Part 3

Calculate the test statistic, $T$.

### Answer Section

## Part 4

Calculate the degrees of freedom, $df$.

### Answer Section

## Part 5

Find the p-value.

### Answer Section

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

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

<!-- ### pl-answer-panel -->

<!-- Since p-value $>0.05$, fail to reject $H_0$. -->

<!-- The data do not provide strong evidence that
New Yorkers sleep more or less than ${{ params.sleep_hours }}$ hours per night
on average -->

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)