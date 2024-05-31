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
    params_vars_title: Global warming, Part I
    params_part1_ans1_value: For each observation in one data set, there is exactly
      one specially corresponding observation in the other data set for the same geographic
      location. The data are paired.
    params_part1_ans1_feedback: Correct!
    params_part1_ans2_value: The observations collected in 1948 and 2018 are completely
      independent of each other, with no relationship between the data sets. The data
      is unpaired.
    params_part1_ans2_feedback: Incorrect!
    params_part1_ans3_value: The data from 1948 and 2018 were collected using different
      methodologies and technologies, making direct comparisons inappropriate. The
      data is unpaired.
    params_part1_ans3_feedback: Incorrect!
    params_part1_ans4_value: Observations from 1948 are used as a control group, while
      the 2018 data acts as the experimental group, implying a cause-and-effect relationship
      between the two years. The observations are therefore not paired but are part
      of a comparative study to measure the impact of time on temperature changes.
    params_part1_ans4_feedback: Incorrect!
    params_part2_ans1_value: '$H_0: \mu_{2018} = \mu_{1948}$ (The average temperature
      in 2018 is equal to the average temperature in 1948 at NOAA stations). $H_A:
      \mu_{2018} > \mu_{1948}$ (The average temperature in 2018 is higher than in
      1948).'
    params_part2_ans1_feedback: Incorrect!
    params_part2_ans2_value: '$H_0: \mu_{2018} > \mu_{1948}$ (The average number of
      days exceeding 90°F in 2018 is greater than in 1948 at NOAA stations). $H_A:
      \mu_{2018} \leq \mu_{1948}$ (The average number of days exceeding 90°F in 2018
      is not greater than in 1948).'
    params_part2_ans2_feedback: Incorrect!
    params_part2_ans3_value: '$H_0: p_{2018} = 0.5$ (The proportion of days exceeding
      90°F in 2018 is 50%). $H_A: p_{2018} ≠ 0.5$ (The proportion of days exceeding
      90°F in 2018 is not 50%).'
    params_part2_ans3_feedback: Incorrect!
    params_part2_ans4_value: '$H_0: \mu_{diff} = 0$ (There is no difference in average
      number of days exceeding 90°F in 1948 and 2018 for NOAA stations). $H_A: \mu_{diff}
      ≠ 0$ (There is a difference).'
    params_part2_ans4_feedback: Correct!
    params_part3_ans1_value: Locations were randomly sampled.
    params_part3_ans1_feedback: Correct!
    params_part3_ans2_value: Observations within pairs are independent.
    params_part3_ans2_feedback: Correct!
    params_part3_ans3_value: Sample size is adequate.
    params_part3_ans3_feedback: Correct!
    params_part3_ans4_value: Outliers are extreme.
    params_part3_ans4_feedback: Incorrect!
    params_part3_ans5_value: Observations within pairs are dependent.
    params_part3_ans5_feedback: Incorrect!
    params_part6_ans1_value: Since the p-value is less than 0.05, we reject $H_0$.
      The data provide strong evidence that NOAA stations observed more 90°F days
      in 2018 than in 1948.
    params_part6_ans1_feedback: Correct!
    params_part6_ans2_value: Since the p-value is greater than 0.05, we fail to reject
      $H_0$. The data do not provide strong evidence that NOAA stations observed more
      90°F days in 2018 than in 1948.
    params_part6_ans2_feedback: Incorrect!
    params_part7_ans1_value: Type 1 Error, since we may have incorrectly rejected
      $H_0$. This error would mean that NOAA stations did not actually observe a decrease,
      but the sample we took just so happened to make it appear that this was the
      case
    params_part7_ans1_feedback: Correct!
    params_part7_ans2_value: Type II Error, since we may have failed to reject $H_0$
      incorrectly. This error would mean that NOAA stations did actually observe a
      decrease in the number of 90°F days in 2018 compared to 1948, but the sample
      we took was not able to provide enough evidence to demonstrate this decrease.
    params_part7_ans2_feedback: Incorrect!
    params_part8_ans1_value: No, since we rejected $H_0$, which had a null value of
      0.
    params_part8_ans1_feedback: Correct!
    params_part8_ans2_value: Yes, since we failed to reject $H_0$, which suggests
      the average difference between the number of days exceeding 90°F from 1948 and
      2018 might include 0.
    params_part8_ans2_feedback: Incorrect!
    params_sample_size: 198
    params_mean_difference: 2.7
    params_std_deviation: 16.4
---
# {{ params_vars_title }}
Let's consider a limited set of climate data, examining temperature differences in 1948 vs 2018. We sampled {{ params.sample_size }} locations from the National Oceanic and Atmospheric Administration’s (NOAA) historical data, where the data was available for both years of interest. We want to know: were there more days with temperatures exceeding 90°F in 2018 or in 1948? The difference in number of days exceeding 90°F (number of days in 2018 - number of days in 1948) was calculated for each of the {{ params.sample_size }} locations. The average of these differences was {{ params.mean_difference }} days with a standard deviation of {{ params.std_deviation }} days. We are interested in determining whether these data provide strong evidence that there were more days in 2018 that exceeded 90°F from NOAA’s weather stations.

## Part 1

Is there a relationship between the observations collected in 1948 and 2018? Or are the observations in the two groups independent?

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

### pl-answer-panel

For each observation in one data set, there is exactly one specially corresponding observation in the other data set for the same geographic location. The data are paired.

## Part 2

Write hypotheses for this research in symbols and in words.

### Answer Section

- {{ params_part2_ans1_value }}
- {{ params_part2_ans2_value }}
- {{ params_part2_ans3_value }}
- {{ params_part2_ans4_value }}

### pl-answer-panel

$H_0: \mu\_{\text{diff}} = 0$ (There is no difference in average number of days exceeding 90\textdegree{}F in 1948 and ${{ params.part1.num2 }}$ for NOAA stations.) $H_A: \mu\_{\text{diff}} \neq 0$ (There is a difference.)

## Part 3

Check the conditions required to complete this test. A histogram of the differences is given.

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}
- {{ params_part3_ans5_value }}

### pl-answer-panel

Locations were randomly sampled, so independence is reasonable. The sample size is at least 30, so we're just looking for particularly extreme outliers: none are present (the observation off left in the histogram would be considered a clear outlier, but not a particularly extreme one). Therefore, the conditions are satisfied

## Part 4

Calculate the test statistic.

### Answer Section

Please enter a numeric value in.

## Part 5

What is the p-value?

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

$SE = 17.2 / \sqrt{197} = 1.23$.
$T = \frac{2.9 - 0}{1.23} = 2.36$ with degrees of freedom df = 197−1 = 196. This leads to a one-tail area of 0.0096 and a p-value of about 0.019.

## Part 6

Use $\alpha = 0.05$ to evaluate the test, and interpret your conclusion in context.

### Answer Section

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}

## Part 7

What type of error might we have made? Explain in context what the error means.

### Answer Section

- {{ params_part7_ans1_value }}
- {{ params_part7_ans2_value }}

### pl-answer-panel

Type~1 Error, since we may have incorrectly rejected $H_0$. This error would mean that NOAA stations did not actually observe a decrease, but the sample we took just so happened to make it appear that this was the case

## Part 8

Based on the results of this hypothesis test, would you expect a confidence interval for the average difference between the number of days exceeding 90°F from 1948 and 2018 to include 0?

### pl-answer-panel

No, since we rejected $H_0$, which had a null value of 0.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)