---
title: Study abroad
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 6.1.1.3
- 6.1.1.5
- 6.1.1.6
- 6.1.1.7
- 6.1.1.8
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
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Lower Limit = '
part3:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Upper Limit = '
    suffix: ''
part4:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer1.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Study abroad
        n: 1614
        p: 62.0
        confidence_level: 95.0
        lower_bound: !!python/object/apply:numpy.core.multiarray.scalar
        - &id001 !!python/object/apply:numpy.dtype
          args:
          - f8
          - false
          - true
          state: !!python/tuple
          - 3
          - <
          - null
          - null
          - null
          - -1
          - -1
          - 0
        - !!binary |
          hlrTvOMU4z8=
        lower_bound_percent: 60
        upper_bound: !!python/object/apply:numpy.core.multiarray.scalar
        - *id001
        - !!binary |
          Ke0NvjCZ5D8=
        upper_bound_percent: 64
      part1:
        ans1:
          value: Yes. The sample is a perfect representation of all high school seniors.
          feedback: Incorrect.
        ans2:
          value: Yes. The sample is a perfect representation of all students who took
            the SAT.
          feedback: Incorrect.
        ans3:
          value: No. The sample only represents students who completed the web survey.
          feedback: Incorrect.
        ans4:
          value: No. The sample only represents students who took the SAT, and this
            was also an online survey.
          feedback: Correct!
      part5:
        ans1:
          value: 95% confidence means that if we repeated this survey 100 times, 95
            of the results would fall within this interval.
          feedback: Incorrect.
        ans2:
          value: 95% confidence means that we are 95% certain that the true proportion
            is within this interval.
          feedback: Incorrect.
        ans3:
          value: 95% confidence means that 95% of the time the true proportion will
            fall within this interval.
          feedback: Incorrect.
        ans4:
          value: 95% of such random samples would produce a 95% confidence interval
            that includes the true proportion.
          feedback: Correct!
      part6:
        ans1:
          value: No. The interval lies entirely above 50%.
          feedback: Incorrect.
        ans2:
          value: Yes. The interval lies entirely below 50%.
          feedback: Incorrect.
        ans3:
          value: No. The interval lies entirely below 50%.
          feedback: Incorrect.
        ans4:
          value: Yes. The interval lies entirely above 50%.
          feedback: Correct!
---
# {{ params.vars.title }}
A survey on {{  params.vars.n }} high school seniors who took the SAT and who completed an optional web survey shows that {{ params.vars.p }}% of high school seniors are fairly certain that they will participate in a study abroad program in college.

## Part 1

Is this sample a representative sample from the population of all high school seniors in the US? Yes or No?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2: (a)

Let's suppose the conditions for inference are met. Even if your answer to Part 1 indicated that this approach would not be reliable, this analysis may still be interesting to carry out (though not report). Calculate the lower bound of a {{ params.vars.confidence_level }}% confidence interval for the proportion of high school seniors (of those who took the SAT) who are fairly certain they will participate in a study abroad program in college, and interpret this interval in context.

### Answer Section

Please enter in a numeric value.

## Part 2: (b)

Calculate the upper bound of a {{ params.vars.confidence_level }}% confidence interval for the proportion of high school seniors (of those who took the SAT) who are fairly certain they will participate in a study abroad program in college.

### Answer Section

Please enter in a numeric value.

## Part 2: (c)

In one sentence interpret this interval in context.

### Answer Section

Please enter in a text response.

## Part 3

What does "{{ params.vars.confidence_level }}% confidence" mean?

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}

## Part 4

Based on this interval, would it be appropriate to claim that the majority of high school seniors are fairly certain that they will participate in a study abroad program in college? Yes or No?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)