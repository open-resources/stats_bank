---
title: Air quality
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
myst:
  substitutions:
    params:
      vars:
        title: Air quality
      part1:
        ans1:
          value: Paired, because data are recorded in the same cities at two different
            time points, and the air quality in a city at one point is not independent
            of the air quality in the same city at another time point.
          feedback: Correct!
        ans2:
          value: Non-paired, because the measurements are from different, non-corresponding
            cities each year so, the air quality in a city at one point is independent
            of the air quality in another city at another time point.
          feedback: Incorrect!
        ans3:
          value: Paired, since air quality is influenced by many varying factors each
            year, making each year's data independent.
          feedback: Incorrect!
        ans4:
          value: Non-paired, because data are recorded in the same cities at two different
            time points, and the air quality in a city at one point is not independent
            of the air quality in the same city at another time point.
          feedback: Incorrect!
      country_capitals: 27
      year_1: 2010
      year_2: 2015
      selected_scenario: in the same cities
---
# {{ params.vars.title }}
Air quality measurements were collected in a random sample of ${{ params.country_capitals }}$ country capitals in ${{ params.year_1 }}$, and then again {{ params.selected_scenario }} in ${{ params.year_2 }}$. We would like to use these data to compare average air quality between the two years.

## Part 1

Should we use a paired or non-paired test? Explain your reasoning.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)