---
title: 'Experimental Design: Sleep Deprivation'
topic: Sampling and Design
author: Gavin Kendal-Freedman
source: 1.4
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 10.1.1.12
- 10.1.1.14
- 10.1.1.21
difficulty:
- medium
randomization:
- undefined
taxonomy:
- undefined
span:
- undefined
length:
- undefined
tags:
- GKF
assets: null
part1:
  type: matching
  pl-customizations:
    weight: 2
    blank: true
part2:
  type: checkbox
  pl-customizations:
    weight: 1
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: multiple-choice
  pl-customizations:
    weight: 1
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
part7:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: 'Experimental Design: Sleep Deprivation'
        num_drivers: 14
        hours_deprivation: 23
        treatment_order: The control treatment was trialed first.
        mentioned_test: reaction time
        driver_type: professional
      part1:
        option1:
          value: Amount of Sleep Deprivation
          name: Explanatory
        option2:
          value: Performance Measured across Various Tasks
          name: Response
        option3:
          value: Hours of Sleep Deprivation
        option4:
          value: Numbers of Drivers
        option5:
          value: Participant Skill
        option6:
          value: reaction time
        statement1:
          value: Explanatory Variable
          matches: Explanatory
        statement2:
          value: Response Variable
          matches: Response
      part2:
        ans1:
          value: Normal Sleep
          feedback: Correct!
        ans2:
          value: 23 hours of sleep deprivation
          feedback: Correct!
        ans3:
          value: 14 hours of sleep deprivation
          feedback: Try again please!
        ans4:
          value: 14 professional drivers
          feedback: Try again please!
        ans5:
          value: 23 professional drivers
          feedback: Try again please!
      part3:
        ans1:
          value: 14 professional drivers
          feedback: Correct!
        ans2:
          value: 23 hours of sleep deprivation
          feedback: Try again please!
        ans3:
          value: 14 hours of sleep deprivation
          feedback: Try again please!
        ans4:
          value: 23 professional drivers
          feedback: Try again please!
      part4:
        ans1:
          value: Yes, there are lurking variables.
          feedback: This is incorrect. Since all drivers participated in both treatments,
            there are no lurking variables.
        ans2:
          value: No, there are no lurking variables.
          feedback: Correct! As all drivers participated in both treatments, there
            are no lurking variables.
      part5:
        ans1:
          value: There are no issues with the treatment order.
          feedback: Try again please! The treatments were not assigned in random order.
        ans2:
          value: The second treatment might have artificially higher scores.
          feedback: Correct! Since all drivers get the treatments in the same order,
            whichever treatment is second will always benefit from any potential learning
            effect.
        ans3:
          value: The first treatment might have artificially higher scores.
          feedback: Try again please!
      part6:
        ans1:
          value: Normal Sleep
          feedback: Correct!
        ans2:
          value: 23 hours of sleep deprivation
          feedback: Try again please! This is a treatment, but not the control.
        ans3:
          value: 14 hours of sleep deprivation
          feedback: Try again please!
        ans4:
          value: 14 professional drivers
          feedback: Try again please!
        ans5:
          value: 23 professional drivers
          feedback: Try again please!
      part7:
        ans1:
          value: Blinding is important the researchers evaluating the performance
            of the subject's cannot bias their evaluations based on the treatment.
          feedback: Correct!
        ans2:
          value: Blinding is important to limit bias, but there is no need for blinding
            in this study.
          feedback: Try again please!
        ans3:
          value: Blinding is not important.
          feedback: Try again please!
---
# {{ params.vars.title }}
How does sleep deprivation affect your ability to drive? A recent study measured the effects on {{ params.vars.num_drivers }} {{ params.vars.driver_type }} drivers.
Each driver participated in two experimental sessions: one after normal sleep and one after {{ params.vars.hours_deprivation }} hours of total sleep deprivation.
{{ params.vars.title }} In each session, performance was measured on a variety of tasks including a {{ params.vars.mentioned_test }}.

The following questions ask you to correctly identify/explain parts of the experimental design of this study.

## Variables

Please identify which of the following variables is the explanatory variable, and which is the response variable.

## Treatments

Which of the following are the treatments used in the experiment?

### Answer Section

- {{ params.part2.ans1.value}}
- {{ params.part2.ans2.value}}
- {{ params.part2.ans3.value}}
- {{ params.part2.ans4.value}}
- {{ params.part2.ans5.value}}

## Experimental Units

Which of the following correctly identifies the experimental units of the study?

### Answer Section

- {{ params.part3.ans1.value}}
- {{ params.part3.ans2.value}}
- {{ params.part3.ans3.value}}
- {{ params.part3.ans4.value}}

## Lurking Variables

Were there any lurking variables in this study?

### Answer Section

- {{ params.part4.ans1.value}}
- {{ params.part4.ans2.value}}

## Treatment Order

Which of the following describes the issue with the treatment order in this study?

### Answer Section

- {{ params.part5.ans1.value}}
- {{ params.part5.ans2.value}}
- {{ params.part5.ans3.value}}

## Control/Placebo

Please identify which of the following is the control treatment in this study.

### Answer Section

- {{ params.part6.ans1.value}}
- {{ params.part6.ans2.value}}
- {{ params.part6.ans3.value}}
- {{ params.part6.ans4.value}}
- {{ params.part6.ans5.value}}

## Blinding

Please identify what the importance of blinding is in this study.

### Answer Section

- {{ params.part7.ans1.value}}
- {{ params.part7.ans2.value}}
- {{ params.part7.ans3.value}}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)