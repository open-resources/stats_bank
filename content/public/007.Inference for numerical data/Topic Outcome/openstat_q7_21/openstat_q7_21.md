---
title: Global warming, Part II
topic: Inference for numerical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
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
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    rtol: 0.02
    weight: 1
    allow-blank: true
    label: 'Lower Bound = '
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    rtol: 0.02
    weight: 1
    allow-blank: true
    label: 'Upper Bound = '
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params_vars_title: Global warming, Part II
    params_part3_ans1_value: We are 81% confident that there was an increase of [lower
      bound] to [upper bound] in the average number of days that hit 90°F in 2018
      relative to 1948 for NOAA stations.
    params_part3_ans1_feedback: Correct!
    params_part3_ans2_value: There is a 81% probability that the true average difference
      in the number of days exceeding 90°F between 1948 and 2018 lies between [lower
      bound] and [upper bound].
    params_part3_ans2_feedback: Incorrect! This statement misinterprets the confidence
      interval as a probability statement about the data rather than about the interval.
    params_part3_ans3_value: There is a 81% probability that the number of days exceeding
      90°F will be between [lower bound] and [upper bound] days higher in 2018 compared
      to 1948 for all locations.
    params_part3_ans3_feedback: Incorrect! This statement suggests a predictive interpretation
      of the confidence interval, which is not accurate.
    params_part3_ans4_value: There is a 81% probability that the observed average
      difference of days exceeding 90°F between 1948 and 2018 is exactly between [lower
      bound] and [upper bound] days.
    params_part3_ans4_feedback: Incorrect! This statement misunderstands the confidence
      interval as a statement about the probability of the observed data, rather than
      about the estimation of the population parameter.
    params_part4_ans1_value: Yes, since the interval lies entirely above 0.
    params_part4_ans1_feedback: Correct!
    params_part4_ans2_value: No, since the interval is not entirely lying above 0.
    params_part4_ans2_feedback: Try again please!
    params_sample_size: 201
    params_mean_difference: 3.0
    params_std_deviation: 16.7
    params_part1_confidence_level: 81
---
# {{ params_vars_title }}
Let's consider a limited set of climate data, examining temperature differences in 1948 vs 2018. We sampled {{ params.sample_size }} locations from the National Oceanic and Atmospheric Administration’s (NOAA) historical data, where the data was available for both years of interest. We considered the change in the number of days exceeding 90°F from 1948 and 2018 at {{ params.sample_size }} randomly sampled locations from the NOAA database. The mean and standard deviation of the reported differences are {{ params.mean_difference }} days and {{ params.std_deviation }} days.

## Part 1

Calculate the lower bound of a {{ params.part1_confidence_level }}% confidence interval for the average difference between number of days exceeding 90°F between 1948 and 2018. We’ve already checked the conditions for you.

### Answer Section

Please enter a numeric value in.

## Part 2

Calculate the upper bound of a {{ params.part1_confidence_level }}% confidence interval for the average difference between number of days exceeding 90°F between 1948 and 2018. We’ve already checked the conditions for you.

### Answer Section

Please enter a numeric value in.

## Part 3

Interpret the interval in context.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}

### pl-answer-panel

We are ${{ params.part1.num1 }}$% confident that there was an
increase of 0.87 to 4.93 in the average number
of days that hit 90\textdegree{}F in 2018
relative to ${{ params.part1.num3 }}$ for NOAA stations

## Part 4

Does the confidence interval provide convincing evidence that there were more days exceeding 90°F in
2018 than in 1948 at NOAA stations? Explain.

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}

### pl-answer-panel

Yes, since the interval lies entirely above~0

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)