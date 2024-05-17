---
title: Exclusive relationships
topic: Inference for numerical data
author: Larita Kipkeu
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.12
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
- LK
assets: null
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $CI_{lower}= $
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $CI_{upper}= $
part3:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
myst:
  substitutions:
    params_vars_title: Exclusive relationships
    params_sample_mean: 3.37
    params_sample_size: 193
    params_sample_std: 1.66
    params_confidence_level: 93
    params_n: 193
    params_part3_ans1_value: 'Independence: it is a random sample, so we can assume
      that the students in this sample are independent of each other with respect
      to number of exclusive relationships they have been in.'
    params_part3_ans1_feedback: Great! You got it.
    params_part3_ans2_value: There are no students who have had no exclusive relationships
      in the sample, which suggests some student responses are likely missing
    params_part3_ans2_feedback: Great! You got it.
    params_part3_ans3_value: The sample size is at least 30, and there are no particularly
      extreme outliers, so the normality condition is reasonable.
    params_part3_ans3_feedback: Great! You got it.
    params_part3_ans4_value: We are $93$% confident that undergraduate students have
      been in (lower_interval) to (upper_interval) exclusive relationships, on average.
    params_part3_ans4_feedback: Great! You got it.
    params_part3_ans5_value: The sample size is at least 30, but there are extreme
      outliers, so the normality condition is unreasonable.
    params_part3_ans5_feedback: Incorrect! Analyze the histogram again.
    params_part3_ans6_value: We are $100$% certain that undergraduate students have
      been in (lower_interval) to (upper_interval) exclusive relationships, on average.
    params_part3_ans6_feedback: Incorrect! This is not the correct way of expressing
      our confidence.
---
# {{ params_vars_title }}
A survey conducted on a reasonably random sample of ${{params_n}}$ undergraduates asked, among many other questions, about the number of exclusive relationships these students have been in. The histogram below shows the distribution of the data from this sample.The sample average is ${{params.sample_mean}}$ with a standard deviation of ${{params.sample_std}}$.
<pl-figure file-name="figure 1.png" type="dynamic" width="450px"></pl-figure>

## Part 1

Estimate the confidence interval of exclusive relationships Duke students have been in using a ${{params.confidence_level}}$% confidence level.

Lower Interval:

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Independence: it is a random sample, so we can assume that the students in this sample are independent of each other for number of exclusive relationships they have been in.
Notice that there are no students who have had exclusive relationships in the sample, which suggests some student responses are likely missing (perhaps only positive values were reported).
The sample size is at least 30, and there are no particularly extreme outliers, so the normality condition is reasonable.
90% CI: (2.97, 3.43).
We are ${{ params.description.num16 }}$% confident that undergraduate students have been in 2.97 to 3.43 exclusive relationships, on average.

## Part 2

Upper Interval:

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

## Part 3

Based on your observations from the graph, conditions required for inference, and any assumptions you made to proceed with your calculations, which of the following statements are correct?

### Answer Section

- {{ params_part3_ans1_value }} {{ params.vars.units}}
- {{ params_part3_ans2_value }} {{ params.vars.units}}
- {{ params_part3_ans3_value }} {{ params.vars.units}}
- {{ params_part3_ans4_value }} {{ params.vars.units}}
- {{ params_part3_ans5_value }} {{ params.vars.units}}
- {{ params_part3_ans6_value }} {{ params.vars.units}}

### pl-answer-panel

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)