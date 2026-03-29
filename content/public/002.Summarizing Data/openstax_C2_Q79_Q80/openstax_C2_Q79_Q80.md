---
title: Expensive TShirts
topic: Summarizing Data
author: Larita Kipkeu
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
- LK
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Expensive TShirts
      num_people: 114
      tshirts: 3
      tshirt_counts:
      - 1
      - 4
      - 3
      - 4
      - 8
      - 7
      - 3
      - 8
      - 1
      - 7
      - 0
      - 3
      - 9
      - 5
      - 7
      - 2
      - 4
      - 9
      - 4
      - 3
      - 1
      - 5
      - 2
      - 8
      - 4
      - 1
      - 8
      - 3
      - 2
      - 0
      - 6
      - 7
      - 6
      - 6
      - 5
      - 4
      - 2
      - 8
      - 8
      - 1
      - 9
      - 7
      - 9
      - 8
      - 1
      - 6
      - 1
      - 1
      - 0
      - 3
      - 2
      - 6
      - 0
      - 2
      - 0
      - 8
      - 1
      - 8
      - 9
      - 0
      - 6
      - 1
      - 1
      - 8
      - 0
      - 8
      - 5
      - 0
      - 8
      - 8
      - 2
      - 9
      - 5
      - 1
      - 9
      - 2
      - 0
      - 4
      - 1
      - 3
      - 5
      - 8
      - 1
      - 9
      - 2
      - 1
      - 0
      - 5
      - 3
      - 2
      - 2
      - 3
      - 3
      - 0
      - 8
      - 1
      - 1
      - 1
      - 0
      - 5
      - 2
      - 4
      - 2
      - 1
      - 9
      - 9
      - 2
      - 1
      - 7
      - 3
      - 9
      - 9
      - 7
      - 7
      part1:
        ans1:
          value: '50.0'
          feedback: You got it!
        ans2:
          value: '25.0'
          feedback: Try again please!
        ans3:
          value: '59.0'
          feedback: Try again please!
        ans4:
          value: Cannot be determined.
          feedback: Try again please!
      part2:
        ans1:
          value: convenience
          feedback: You got it!
        ans2:
          value: stratified
          feedback: Try again please!
        ans3:
          value: simple random
          feedback: Try again please!
        ans4:
          value: cluster
          feedback: Try again please!
---
# {{ params.vars.title }}
Suppose ${{ params.num_people }}$ people who shopped in a special T-shirt store were asked the number of T-shirts they own costing more than $19 each.

<pl-figure file-name="figure1.png" type="dynamic" width="500px"></pl-figure>

## Part 1

The percentage of people who own at most ${{ params.tshirts }}$ T-Shirts costing more than $19 each is approximately:

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

If the data were collected by asking the first ${{ params.num_people }}$ people who entered the store, then the type of sampling is:

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)