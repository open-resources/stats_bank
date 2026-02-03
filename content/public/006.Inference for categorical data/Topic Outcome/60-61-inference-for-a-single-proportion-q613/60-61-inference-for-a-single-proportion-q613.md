---
title: Taste test
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- undefined
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
- sample.html
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $Z=$
part4:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: true
    label: p-value=
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer1.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
myst:
  substitutions:
    params:
      vars:
        title: Taste Test
        sample: 96
        p_value: 0.838256486385826
      part1:
        ans1:
          value: '$H_0: p = 0.49$, $H_A: p ≠ 0.5$'
          feedback: Try again please!
        ans2:
          value: '$H_0: p = 0.49$, $H_A: p = 0.5$'
          feedback: Try again please!
        ans3:
          value: '$H_0: p = 0.5$, $H_A: p ≠ 0.5$'
          feedback: Correct!
        ans4:
          value: '$H_0: p ≠ 0.5$, $H_A: p = 0.5$'
          feedback: Try again please!
      part2:
        ans1:
          value: Since this is a random sample, independence is satisfied. The success-failure
            condition is also satisfied as we (using $p_0 = 0.5$, we expect 48 successes
            and 48 failures).
          feedback: Correct!
        ans2:
          value: Since this is a random sample, independence is satisfied. The success-failure
            condition is not satisfied, as our expectation of 48 successes and 48
            failures, using $p_0 = 0.5$, is not met.
          feedback: Try again please!
        ans3:
          value: Given this is not a random sample, independence is not satisfied.
            The success-failure condition is also satisfied as we (using $p_0 = 0.5$,
            we expect 48 successes and 48 failures).
          feedback: Try again please!
      part5:
        ans1:
          value: Since the p-value $< 0.05$, we reject the null hypothesis. Since
            we rejected $H_0$ and the point estimate suggests people are better than
            random guessing, we can conclude the rate of correctly identifying a soda
            for these people is significantly better than just by random guessing.
          feedback: Try again please!
        ans2:
          value: Since the p-value $≥ 0.05$, we fail to reject the null hypothesis.
            Since we did not reject $H_0$ and the point estimate suggests people are
            not better than random guessing, we cannot conclude that the rate of correctly
            identifying a soda for these people is significantly better than just
            by random guessing.
          feedback: Correct!
---
# {{ params.vars.title }}
Some people claim that they can tell the difference between a diet soda and a regular soda in the first sip. A researcher wanting to test this claim randomly sampled {{ params.vars.sample }} such people. He then filled {{ params.vars.sample }} plain white cups with soda, half diet and half regular through random assignment, and asked each person to take one sip from their cup and identify the soda as diet or regular. {{ params.vars.num_correct_identifications }} participants correctly identified the soda. Do these data provide strong evidence that these people are any better or worse than random guessing at telling the difference between diet and regular soda? Yes or No?

## Part 1

State the null and alternative hypotheses for the taste test.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Do the criteria for independence and the success-failure condition hold true?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

Calculate the test statistic.

### Answer Section

Please enter in a numeric value.

## Part 4

Determine the p-value from the calculated test statistic.

### Answer Section

Please enter in a numeric value.

## Part 5

Based on the p-value and a significance level of 0.05, state whether you will reject or fail to reject the null hypothesis and explain the conclusion.

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}

## Part 6

Interpret the p-value in this context.

### Answer Section

Please enter in a text response.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)