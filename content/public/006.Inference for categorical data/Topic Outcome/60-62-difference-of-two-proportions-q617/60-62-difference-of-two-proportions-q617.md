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
    params:
      vars:
        title: Social experiment, Part I
      inter_provoc: 8
      non_inter_provoc: 20
      total_provoc: 28
      inter_cons: 16
      non_inter_cons: 13
      total_cons: 29
      part1:
        ans1:
          value: This is not a randomized experiment, and it is unclear whether people
            would be affected by the behavior of their peers.
          feedback: Correct!
        ans2:
          value: Independence may not hold.
          feedback: Correct!
        ans3:
          value: There are not enough interventions under the provocative scenario,
            so the success-failure condition does not hold.
          feedback: Correct!
        ans4:
          value: The success-failure condition is not being satisfied.
          feedback: Correct!
        ans5:
          value: This is a randomized experiment, and it is clear that people would
            be affected by the behavior of their peers.
          feedback: Incorrect!
        ans6:
          value: Independence holds.
          feedback: Incorrect!
        ans7:
          value: There are sufficient interventions under all of the scenarios, so
            the success-failure condition holds.
          feedback: Incorrect!
        ans8:
          value: The success-failure condition is being satisfied.
          feedback: Incorrect!
---
# {{ params.vars.title }}
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

- {{ params.part1.ans1.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)