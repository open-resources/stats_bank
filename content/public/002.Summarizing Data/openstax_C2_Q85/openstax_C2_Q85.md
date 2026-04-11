---
title: Population Age Demographics Boxplot
topic: Summarizing Data
author: Christina Yang
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 2.1.1.4
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
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 1
    weight: 1
    allow-blank: false
    suffix: '%'
myst:
  substitutions:
    params:
      vars:
        title: Population Age Demographics Boxplot
      country: Germany
      percent_senior: 13.2
      median: 45
      q1: 17
      q3: 59
      whislow: 0
      whishigh: 110
      part1:
        ans1:
          value: more children
          feedback: Correct! The left whisker shows that 25% of the population are
            children 17 and younger. The right whisker shows that 25% of the population
            are adults 59 and older, so adults 65 and over represent less than 25%.
        ans2:
          value: fewer children
          feedback: 'Hint: the left whisker shows that 25% of the population are children
            17 and younger. The right whisker shows that 25% of the population are
            adults 59 and older.'
---
# {{ params.vars.title }}
The following box plot shows the {{ params.country }} population for a certain year.

<pl-figure file-name="figure1.png" type="dynamic" width="500px"></pl-figure>

## Part 1

Are there fewer or more children (age 17 and under) than senior citizens (age 65 and over)?

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}

## Part 2

{{ params.percent_senior }}% are age 65 and over. Approximately what percentage of the population are working age adults (above age 17 to age 65)?

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)