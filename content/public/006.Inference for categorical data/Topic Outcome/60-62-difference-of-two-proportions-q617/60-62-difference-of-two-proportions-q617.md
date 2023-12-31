---
title: Social experiment, Part I
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.2
- 6.1.1.3
- 6.1.1.13
- 6.1.1.16
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
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
myst:
  substitutions:
    params_vars_title: Social experiment, Part I
    params_inter_provoc: 8
    params_non_inter_provoc: 17
    params_total_provoc: 25
    params_inter_cons: 19
    params_non_inter_cons: 15
    params_total_cons: 34
    params_part1_ans1_value: This is not a randomized experiment, and it is unclear
      whether people would be affected by the behavior of their peers.
    params_part1_ans1_feedback: Correct!
    params_part1_ans2_value: Independence may not hold.
    params_part1_ans2_feedback: Correct!
    params_part1_ans3_value: There are not enough interventions under the provocative
      scenario, so the success-failure condition does not hold.
    params_part1_ans3_feedback: Correct!
    params_part1_ans4_value: The success-failure condition is not being satisfied.
    params_part1_ans4_feedback: Correct!
    params_part1_ans5_value: This is a randomized experiment, and it is clear that
      people would be affected by the behavior of their peers.
    params_part1_ans5_feedback: Incorrect!
    params_part1_ans6_value: Independence holds.
    params_part1_ans6_feedback: Incorrect!
    params_part1_ans7_value: There are sufficient interventions under all of the scenarios,
      so the success-failure condition holds.
    params_part1_ans7_feedback: Incorrect!
    params_part1_ans8_value: The success-failure condition is being satisfied.
    params_part1_ans8_feedback: Incorrect!
---
# {{ params_vars_title }}
A "social experiment" conducted by a TV program questioned what people do when they see a very obviously bruised woman getting picked on by her boyfriend. On two different occasions at the same restaurant, the same couple was depicted. In one scenario the woman was dressed "provocatively" and in the other scenario the woman was dressed "conservatively". The table below shows how many restaurant diners were present under each scenario, and whether or not they intervened.

|               |               | **Scenario**                    |                             |
|---------------|---------------|---------------------------------|-----------------------------|
|               |               | **Provocative**                 | **Conservative**            |
|---------------|---------------|---------------------------------|-----------------------------|
| **Intervene** | **Yes**       | {{ params.inter_provoc}}        | {{ params.inter_cons }}     |
|               | **No**        | {{ params.non_inter_provoc }}   | {{ params.non_inter_cons }} |
|---------------|---------------|---------------------------------|-----------------------------|
|               | **Total**     | {{ params.total_provoc }}       | {{ params.total_cons }}     |

## Part 1

Which of the following statements explain why the sampling distribution of the difference between the proportions of interventions under provocative and conservative scenarios does not follow an approximately normal distribution.

### Answer Section

- {{ params_part1_ans1_value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)