---
title: Migraine and acupuncture, Part I
topic: Introduction to Data
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 1.1.1.3
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
- CY
assets:
- earacupuncture.jpg
- sample.html
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    weight: 1
    label: $d= $
    suffix: '%'
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    weight: 1
    label: $d= $
    suffix: '%'
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
    fixed-order: true
part4:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer4.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
myst:
  substitutions:
    params_vars_title: Migraine and acupuncture, Part I
    params_table0_r2_c2: 13
    params_table0_r2_c3: 34
    params_table0_r2_c4: 47
    params_table0_r3_c2: 5
    params_table0_r3_c3: 41
    params_table0_r3_c4: 46
    params_table0_r4_c2: 18
    params_table0_r4_c3: 75
    params_table0_r4_c4: 93
    params_part1_num1: 24.0
    params_part3_num1: 24.0
    params_part3_ans1_value: Treatment
    params_part3_ans1_feedback: Correct!
    params_part3_ans2_value: Control
    params_part3_ans2_feedback: This is incorrect. Try again please!
    params_part3_ans3_value: Neither
    params_part3_ans3_feedback: This is incorrect. Try again please!
    params_part3_phrase1: is
    params_part4_num1: 24.0
    params_description_num1: 93
    params_description_num2: 47
    params_description_num3: 46
    params_description_num4: 24.0
    params_part1_ans_before_convert: 0.277
    params_part2_ans_before_convert: 0.109
---
# {{ params_vars_title }}
A migraine is a particularly painful type of headache, which patients sometimes wish to treat with acupuncture. To determine whether acupuncture relieves migraine pain, researchers conducted a randomized controlled study where ${{ params_description_num1 }}$ females diagnosed with migraine headaches were randomly assigned to one of two groups: treatment or control. ${{ params_description_num2 }}$ patients in the treatment group received acupuncture that is specifically designed to treat migraines. ${{ params_description_num3 }}$ patients in the control group received placebo acupuncture (needle insertion at non-acupoint locations). ${{ params_description_num4 }}$ hours after patients received acupuncture, they were asked if they were pain free. Results are summarized in the contingency table below.

| Group | Pain free | Not pain free | Total |
| :------------ | :------------: | :------------: | ------------: |
| Treatment | {{ params_table0_r2_c2 }} | {{ params_table0_r2_c3 }} | {{ params_table0_r2_c4 }} |
| Control | {{ params_table0_r3_c2 }} | {{ params_table0_r3_c3 }} | {{ params_table0_r3_c4 }} |
| Total | {{ params_table0_r4_c2 }} | {{ params_table0_r4_c3 }} | {{ params_table0_r4_c4 }} |

<img height="200" src="earacupuncture.jpg" alt='An ear is show, with an "M" shown near the front lower lobe of the ear and an "S" shown near the middle upper portion of the ear.'>

## Part 1

What percent of patients in the treatment group were pain free ${{ params_part1_num1 }}$ hours after receiving acupuncture? Round to 1 decimal place.

### Answer Section

Please enter in a numeric value in.

### pl-answer-panel

Part 1: Treatment: ${{ params_table0_r2_c2 }}/{{ params_table0_r2_c4 }} = {{ params.part1_ans_before_convert}} \rightarrow {{ correct_answers.part1_ans }}%$

## Part 2

What percent were pain free in the control group? Round to 1 decimal place.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Part 2: Control: ${{ params_table0_r3_c2 }}/{{ params_table0_r3_c4 }} = {{ params.part2_ans_before_convert}} \rightarrow {{ correct_answers.part2_ans }}%$

## Part 3

In which group did a higher percent of patients become pain free ${{ params_part3_num1 }}$ hours after receiving acupuncture?

### Answer Section

- {{ params_part3_ans1_value }}
- {{ params_part3_ans2_value }}

### pl-answer-panel

Part 3: A higher percentage of patients in the treatment group were pain
free {{ params_part1_num1 }} hours after receiving acupuncture

## Part 4

Your findings so far might suggest that acupuncture {{ params_part3_phrase1 }} an effective treatment for migraines for all people who suffer from migraines. However, this is not the only possible conclusion that can be drawn based on your findings so far. What is one other possible explanation for the observed difference between the percentages of patients that are pain free ${{ params_part4_num1 }}$ hours after receiving acupuncture in the two groups?

### Answer Section

### pl-answer-panel

Part 4: It is possible that the observed difference between the two group
percentages is due to chance

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)