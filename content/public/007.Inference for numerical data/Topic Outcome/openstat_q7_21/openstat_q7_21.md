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
    params:
      vars:
        title: Global warming, Part II
      part3:
        ans1:
          value: We are 98% confident that there was an increase of [lower bound]
            to [upper bound] in the average number of days that hit 90°F in 2018 relative
            to 1948 for NOAA stations.
          feedback: Correct!
        ans2:
          value: There is a 98% probability that the true average difference in the
            number of days exceeding 90°F between 1948 and 2018 lies between [lower
            bound] and [upper bound].
          feedback: Incorrect! This statement misinterprets the confidence interval
            as a probability statement about the data rather than about the interval.
        ans3:
          value: There is a 98% probability that the number of days exceeding 90°F
            will be between [lower bound] and [upper bound] days higher in 2018 compared
            to 1948 for all locations.
          feedback: Incorrect! This statement suggests a predictive interpretation
            of the confidence interval, which is not accurate.
        ans4:
          value: There is a 98% probability that the observed average difference of
            days exceeding 90°F between 1948 and 2018 is exactly between [lower bound]
            and [upper bound] days.
          feedback: Incorrect! This statement misunderstands the confidence interval
            as a statement about the probability of the observed data, rather than
            about the estimation of the population parameter.
      part4:
        ans1:
          value: No, since the interval is not entirely lying above 0.
          feedback: Correct!
        ans2:
          value: Yes, since the interval lies entirely above 0.
          feedback: Try again please!
      sample_size: 192
      mean_difference: 2.7
      std_deviation: 18.4
      part1_confidence_level: 98
---
# {{ params.vars.title }}
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

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 4

Does the confidence interval provide convincing evidence that there were more days exceeding 90°F in
2018 than in 1948 at NOAA stations? Explain.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)