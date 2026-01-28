---
title: Global warming, Part I
topic: Inference for numerical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.6
- 7.1.1.7
- 7.1.1.8
- 7.1.1.12
- 7.1.1.19
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
assets:
- global_warming_v2_1_diffs.jpg
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    rtol: 0.01
    weight: 1
    allow-blank: true
    label: $T= $
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    rtol: 0.01
    weight: 1
    allow-blank: true
    label: p-value =
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
part8:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Global warming, Part I
      part1:
        ans1:
          value: For each observation in one data set, there is exactly one specially
            corresponding observation in the other data set for the same geographic
            location. The data are paired.
          feedback: Correct!
        ans2:
          value: The observations collected in 1948 and 2018 are completely independent
            of each other, with no relationship between the data sets. The data is
            unpaired.
          feedback: Incorrect!
        ans3:
          value: The data from 1948 and 2018 were collected using different methodologies
            and technologies, making direct comparisons inappropriate. The data is
            unpaired.
          feedback: Incorrect!
        ans4:
          value: Observations from 1948 are used as a control group, while the 2018
            data acts as the experimental group, implying a cause-and-effect relationship
            between the two years. The observations are therefore not paired but are
            part of a comparative study to measure the impact of time on temperature
            changes.
          feedback: Incorrect!
      part2:
        ans1:
          value: '$H_0: \mu_{2018} = \mu_{1948}$ (The average temperature in 2018
            is equal to the average temperature in 1948 at NOAA stations). $H_A: \mu_{2018}
            > \mu_{1948}$ (The average temperature in 2018 is higher than in 1948).'
          feedback: Incorrect!
        ans2:
          value: '$H_0: \mu_{2018} > \mu_{1948}$ (The average number of days exceeding
            90°F in 2018 is greater than in 1948 at NOAA stations). $H_A: \mu_{2018}
            \leq \mu_{1948}$ (The average number of days exceeding 90°F in 2018 is
            not greater than in 1948).'
          feedback: Incorrect!
        ans3:
          value: '$H_0: p_{2018} = 0.5$ (The proportion of days exceeding 90°F in
            2018 is 50%). $H_A: p_{2018} ≠ 0.5$ (The proportion of days exceeding
            90°F in 2018 is not 50%).'
          feedback: Incorrect!
        ans4:
          value: '$H_0: \mu_{diff} = 0$ (There is no difference in average number
            of days exceeding 90°F in 1948 and 2018 for NOAA stations). $H_A: \mu_{diff}
            ≠ 0$ (There is a difference).'
          feedback: Correct!
      part3:
        ans1:
          value: Locations were randomly sampled.
          feedback: Correct!
        ans2:
          value: Observations within pairs are independent.
          feedback: Correct!
        ans3:
          value: Sample size is adequate.
          feedback: Correct!
        ans4:
          value: Outliers are extreme.
          feedback: Incorrect!
        ans5:
          value: Observations within pairs are dependent.
          feedback: Incorrect!
      part6:
        ans1:
          value: Since the p-value is less than 0.05, we reject $H_0$. The data provide
            strong evidence that NOAA stations observed more 90°F days in 2018 than
            in 1948.
          feedback: Correct!
        ans2:
          value: Since the p-value is greater than 0.05, we fail to reject $H_0$.
            The data do not provide strong evidence that NOAA stations observed more
            90°F days in 2018 than in 1948.
          feedback: Incorrect!
      part7:
        ans1:
          value: Type 1 Error, since we may have incorrectly rejected $H_0$. This
            error would mean that NOAA stations did not actually observe a decrease,
            but the sample we took just so happened to make it appear that this was
            the case
          feedback: Correct!
        ans2:
          value: Type II Error, since we may have failed to reject $H_0$ incorrectly.
            This error would mean that NOAA stations did actually observe a decrease
            in the number of 90°F days in 2018 compared to 1948, but the sample we
            took was not able to provide enough evidence to demonstrate this decrease.
          feedback: Incorrect!
      part8:
        ans1:
          value: No, since we rejected $H_0$, which had a null value of 0.
          feedback: Correct!
        ans2:
          value: Yes, since we failed to reject $H_0$, which suggests the average
            difference between the number of days exceeding 90°F from 1948 and 2018
            might include 0.
          feedback: Incorrect!
      sample_size: 211
      mean_difference: 2.6
      std_deviation: 19.1
---
# {{ params.vars.title }}
Let's consider a limited set of climate data, examining temperature differences in 1948 vs 2018. We sampled {{ params.sample_size }} locations from the National Oceanic and Atmospheric Administration’s (NOAA) historical data, where the data was available for both years of interest. We want to know: were there more days with temperatures exceeding 90°F in 2018 or in 1948? The difference in number of days exceeding 90°F (number of days in 2018 - number of days in 1948) was calculated for each of the {{ params.sample_size }} locations. The average of these differences was {{ params.mean_difference }} days with a standard deviation of {{ params.std_deviation }} days. We are interested in determining whether these data provide strong evidence that there were more days in 2018 that exceeded 90°F from NOAA’s weather stations.

## Part 1

Is there a relationship between the observations collected in 1948 and 2018? Or are the observations in the two groups independent?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Write hypotheses for this research in symbols and in words.

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

Check the conditions required to complete this test. A histogram of the differences is given.

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}
- {{ params.part3.ans5.value }}

## Part 4

Calculate the test statistic.

### Answer Section

Please enter a numeric value in.

## Part 5

What is the p-value?

### Answer Section

Please enter a numeric value in.

## Part 6

Use $\alpha = 0.05$ to evaluate the test, and interpret your conclusion in context.

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}

## Part 7

What type of error might we have made? Explain in context what the error means.

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}

## Part 8

Based on the results of this hypothesis test, would you expect a confidence interval for the average difference between the number of days exceeding 90°F from 1948 and 2018 to include 0?

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)