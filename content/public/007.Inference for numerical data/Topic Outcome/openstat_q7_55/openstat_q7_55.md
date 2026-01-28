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
    params:
      vars:
        title: Exclusive relationships
      sample_mean: 3.58
      sample_size: 185
      sample_std: 1.76
      confidence_level: 87
      n: 185
      part3:
        ans1:
          value: 'Independence: it is a random sample, so we can assume that the students
            in this sample are independent of each other with respect to number of
            exclusive relationships they have been in.'
          feedback: Great! You got it.
        ans2:
          value: There are no students who have had no exclusive relationships in
            the sample, which suggests some student responses are likely missing
          feedback: Great! You got it.
        ans3:
          value: The sample size is at least 30, and there are no particularly extreme
            outliers, so the normality condition is reasonable.
          feedback: Great! You got it.
        ans4:
          value: We are $87$% confident that undergraduate students have been in (lower_interval)
            to (upper_interval) exclusive relationships, on average.
          feedback: Great! You got it.
        ans5:
          value: The sample size is at least 30, but there are extreme outliers, so
            the normality condition is unreasonable.
          feedback: Incorrect! Analyze the histogram again.
        ans6:
          value: We are $100$% certain that undergraduate students have been in (lower_interval)
            to (upper_interval) exclusive relationships, on average.
          feedback: Incorrect! This is not the correct way of expressing our confidence.
---
# {{ params.vars.title }}
A survey conducted on a reasonably random sample of ${{params.n}}$ undergraduates asked, among many other questions, about the number of exclusive relationships these students have been in. The histogram below shows the distribution of the data from this sample.The sample average is ${{params.sample_mean}}$ with a standard deviation of ${{params.sample_std}}$.
<pl-figure file-name="figure 1.png" type="dynamic" width="450px"></pl-figure>

## Part 1

Estimate the confidence interval of exclusive relationships Duke students have been in using a ${{params.confidence_level}}$% confidence level.

Lower Interval:

### Answer Section

Please enter a numeric value in.

## Part 2

Upper Interval:

### Answer Section

Please enter a numeric value in.

## Part 3

Based on your observations from the graph, conditions required for inference, and any assumptions you made to proceed with your calculations, which of the following statements are correct?

### Answer Section

- {{ params.part3.ans1.value }} {{ params.vars.units}}
- {{ params.part3.ans2.value }} {{ params.vars.units}}
- {{ params.part3.ans3.value }} {{ params.vars.units}}
- {{ params.part3.ans4.value }} {{ params.vars.units}}
- {{ params.part3.ans5.value }} {{ params.vars.units}}
- {{ params.part3.ans6.value }} {{ params.vars.units}}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)