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
    params_vars_title: Life after college
    params_vars_ci_low_part4: 0.6421117365069755
    params_vars_ci_high_part4: 0.7316746712600148
    params_vars_ci_low_part4_percent: 64
    params_vars_ci_high_part4_percent: 73
    params_vars_ci_low_part8: 0.6280375610457836
    params_vars_ci_high_part8: 0.7457488467212068
    params_part1_ans1_value: Proportion of graduates from this university who found
      a job within one month of graduating.
    params_part1_ans1_feedback: Incorrect.
    params_part1_ans2_value: Average GPA of graduates from this university within
      one year of graduating.
    params_part1_ans2_feedback: Incorrect.
    params_part1_ans3_value: Total number of faculty members at this university.
    params_part1_ans3_feedback: Incorrect.
    params_part1_ans4_value: Proportion of graduates from this university who found
      a job within one year of graduating.
    params_part1_ans4_feedback: Correct!
    params_description_num1: 283
    params_description_num2: 412
    params_description_num3: 4225
    params_part3_ans1_value: This is not a random sample, so the observations are
      not independent.
    params_part3_ans1_feedback: Incorrect.
    params_part3_ans2_value: 'The success-failure condition is not satisfied: 283
      successes, 129 failures, both below 10.'
    params_part3_ans2_feedback: Incorrect.
    params_part3_ans3_value: 'The success-failure condition is satisfied: 283 successes,
      129 failures, both well above 10.'
    params_part3_ans3_feedback: Correct!
    params_part3_ans4_value: This is a random sample, so the observations are independent.
    params_part3_ans4_feedback: Correct!
    params_num_part4_num1: 95.0
    params_part6_ans1_value: We are $95$% confident that only [lower bound]% to [upper
      bound]% of graduates from this university were employed within six months of
      finishing their undergraduate degree.
    params_part6_ans1_feedback: Incorrect.
    params_part6_ans2_value: We are $95$% confident that nearly [lower bound]% to
      [upper bound]% of graduates from this university didn't manage to find a job
      within one year of completing their undergraduate degree.
    params_part6_ans2_feedback: Incorrect.
    params_part6_ans3_value: We are $95$% confident that about [lower bound]% to [upper
      bound]% of graduates from this university secured employment within five years
      of completing their undergraduate degree.
    params_part6_ans3_feedback: Incorrect.
    params_part6_ans4_value: We are $95%$% confident that approximately [lower bound]%
      to [upper bound]% of graduates from this university found a job within one year
      of completing their undergraduate degree.
    params_part6_ans4_feedback: Correct!
    params_part7_ans1_value: 95% confidence means that if we repeated this survey
      100 times, 95 of the results would fall within this interval.
    params_part7_ans1_feedback: Incorrect.
    params_part7_ans2_value: 95% confidence means that 95% of the graduates found
      jobs within one year of completing their undergraduate degree.
    params_part7_ans2_feedback: Incorrect.
    params_part7_ans3_value: 95% confidence means that the survey was conducted with
      95% accuracy.
    params_part7_ans3_feedback: Incorrect.
    params_part7_ans4_value: 95% of such random samples would produce a 95% confidence
      interval that includes the true proportion of students at this university who
      found a job within one year of graduating from college.
    params_part7_ans4_feedback: Correct!
    params_part8_num1: 99.0
    params_part10_ans1_value: same width
    params_part10_ans1_feedback: Incorrect.
    params_part10_ans3_value: narrower
    params_part10_ans3_feedback: Incorrect.
    params_part10_ans4_value: wider
    params_part10_ans4_feedback: Correct! 99% CI is wider, as we are more confident
      that the true proportion is within the interval and so need to cover a wider
      range
---
# {{ params_vars_title }}
We are interested in estimating the proportion of graduates at a mid-sized university who found a job within one year of completing their undergraduate degree. Suppose we conduct a survey and find out that ${{ params_description_num1 }}$ of the ${{ params_description_num2 }}$ randomly sampled graduates found jobs. The graduating class under consideration included over ${{ params_description_num3 }}$ students.

## Part 1: (a)

Select the population parameter of interest.

### Answer Section

- {{ params_part1_ans1_value }}
- {{ params_part1_ans2_value }}
- {{ params_part1_ans3_value }}
- {{ params_part1_ans4_value }}

## Part 1: (b)

What is the value of the point estimate of this parameter?

### Answer Section

Please enter in a numeric value

### pl-answer-panel

Proportion of graduates from this university who found a job within one year of graduating. $\hat{p} = \frac{ {{ params_description_num1 }} }{ {{ params_description_num2 }} } = {{ params.correct_answers.part2_ans }}$

## Part 2

Check if the conditions for constructing a confidence interval based on these data are met.

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}
- {{ params_part3_ans3_value }}
- {{ params_part3_ans4_value }}

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

- {{ params_part6_ans1_value }}
- {{ params_part6_ans2_value }}
- {{ params_part6_ans3_value }}
- {{ params_part6_ans4_value }}

### pl-answer-panel

Part 3: ({{ params.vars.ci_low_part4 }}, {{ params.vars.ci_high_part4 }}). We are ${{ params.num_part4.num1 }}$% confident that approximately {{ params.vars.ci_low_part4_percent }}% to {{ params.vars.ci_high_part4_percent }}% of graduates from this university found a job within one year of completing their undergraduate degree.

## Part 4

What does "95% confidence" mean?

### Answer Section

- {{ params_part7_ans1_value }}
- {{ params_part7_ans2_value }}
- {{ params_part7_ans3_value }}
- {{ params_part7_ans4_value }}

## Part 5: (a)

Calculate the lower bound of the ${{ params_part8_num1 }}$% confidence interval for the same parameter.

### Answer Section

Please enter in a numeric value in.

## Part 5: (b)

Calculate the upper bound of the ${{ params_part8_num1 }}$% confidence interval for the same parameter.

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