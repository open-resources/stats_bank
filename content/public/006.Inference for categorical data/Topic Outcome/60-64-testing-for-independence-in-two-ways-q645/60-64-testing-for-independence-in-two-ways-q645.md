---
title: Life after college
topic: Inference for categorical data
author: Alejandro Builes
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.0
- 6.1.1.1
- 6.1.1.2
- 6.1.1.3
- 6.1.1.4
- 6.1.1.5
- 6.1.1.6
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
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: $\hat{p} =$
part3:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
part4:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Lower bound of 95% CI = '
part5:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Upper bound of 95% CI = '
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
part8:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Lower bound of 99% CI = '
part9:
  type: number-input
  pl-customizations:
    rtol: 0.01
    weight: 1
    allow-blank: false
    label: 'Upper bound of 99% CI = '
part10:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Life after college
        ci_low_part4: 0.6367834543319499
        ci_high_part4: 0.737449674502406
        ci_low_part4_percent: 64
        ci_high_part4_percent: 74
        ci_low_part8: 0.6209644768765926
        ci_high_part8: 0.7532686519577633
      part1:
        ans1:
          value: Proportion of graduates from this university who found a job within
            one month of graduating.
          feedback: Incorrect.
        ans2:
          value: Average GPA of graduates from this university within one year of
            graduating.
          feedback: Incorrect.
        ans3:
          value: Total number of faculty members at this university.
          feedback: Incorrect.
        ans4:
          value: Proportion of graduates from this university who found a job within
            one year of graduating.
          feedback: Correct!
      description:
        num1: 224
        num2: 326
        num3: 4648
      part3:
        ans1:
          value: This is not a random sample, so the observations are not independent.
          feedback: Incorrect.
        ans2:
          value: 'The success-failure condition is not satisfied: 224 successes, 102
            failures, both below 10.'
          feedback: Incorrect.
        ans3:
          value: 'The success-failure condition is satisfied: 224 successes, 102 failures,
            both well above 10.'
          feedback: Correct!
        ans4:
          value: This is a random sample, so the observations are independent.
          feedback: Correct!
      num_part4:
        num1: 95.0
      part6:
        ans1:
          value: We are $95$% confident that only [lower bound]% to [upper bound]%
            of graduates from this university were employed within six months of finishing
            their undergraduate degree.
          feedback: Incorrect.
        ans2:
          value: We are $95$% confident that nearly [lower bound]% to [upper bound]%
            of graduates from this university didn't manage to find a job within one
            year of completing their undergraduate degree.
          feedback: Incorrect.
        ans3:
          value: We are $95$% confident that about [lower bound]% to [upper bound]%
            of graduates from this university secured employment within five years
            of completing their undergraduate degree.
          feedback: Incorrect.
        ans4:
          value: We are $95%$% confident that approximately [lower bound]% to [upper
            bound]% of graduates from this university found a job within one year
            of completing their undergraduate degree.
          feedback: Correct!
      part7:
        ans1:
          value: 95% confidence means that if we repeated this survey 100 times, 95
            of the results would fall within this interval.
          feedback: Incorrect.
        ans2:
          value: 95% confidence means that 95% of the graduates found jobs within
            one year of completing their undergraduate degree.
          feedback: Incorrect.
        ans3:
          value: 95% confidence means that the survey was conducted with 95% accuracy.
          feedback: Incorrect.
        ans4:
          value: 95% of such random samples would produce a 95% confidence interval
            that includes the true proportion of students at this university who found
            a job within one year of graduating from college.
          feedback: Correct!
      part8:
        num1: 99.0
      part10:
        ans1:
          value: same width
          feedback: Incorrect.
        ans3:
          value: narrower
          feedback: Incorrect.
        ans4:
          value: wider
          feedback: Correct! 99% CI is wider, as we are more confident that the true
            proportion is within the interval and so need to cover a wider range
---
# {{ params.vars.title }}
We are interested in estimating the proportion of graduates at a mid-sized university who found a job within one year of completing their undergraduate degree. Suppose we conduct a survey and find out that ${{ params.description.num1 }}$ of the ${{ params.description.num2 }}$ randomly sampled graduates found jobs. The graduating class under consideration included over ${{ params.description.num3 }}$ students.

## Part 1: (a)

Select the population parameter of interest.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 1: (b)

What is the value of the point estimate of this parameter?

### Answer Section

Please enter in a numeric value

## Part 2

Check if the conditions for constructing a confidence interval based on these data are met.

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Part 3: (a)

Calculate the lower bound of the ${{ params.num_part4.num1 }}$% confidence interval for the proportion of graduates who found a job within one year of completing their undergraduate degree at this university.

### Answer Section

Please enter in a numeric value

## Part 3: (b)

Calculate the upper bound of the ${{ params.num_part4.num1 }}$% confidence interval for the proportion of graduates who found a job within one year of completing their undergraduate degree at this university.

### Answer Section

Please enter in a numeric value

## Part 3: (c)

In one sentence interpret this interval in context.

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Part 4

What does "95% confidence" mean?

### Answer Section

- {{ params.part7.ans1.value }}
- {{ params.part7.ans2.value }}
- {{ params.part7.ans3.value }}
- {{ params.part7.ans4.value }}

## Part 5: (a)

Calculate the lower bound of the ${{ params.part8.num1 }}$% confidence interval for the same parameter.

### Answer Section

Please enter in a numeric value in.

## Part 5: (b)

Calculate the upper bound of the ${{ params.part8.num1 }}$% confidence interval for the same parameter.

### Answer Section

Please enter in a numeric value in.

## Part 6

Compare the widths of the 95% and 99% confidence intervals. Is the 99% confidence interval wider or narrower than the 95% confidence interval? (You can answer this question without having to actually calculate the confidence interval).

### Answer Section

- {{ params.part11.ans1.value }}
- {{ params.part11.ans2.value }}
- {{ params.part11.ans3.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)