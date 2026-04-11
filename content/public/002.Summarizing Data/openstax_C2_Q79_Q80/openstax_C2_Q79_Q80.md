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
      num_people: 131
      tshirts: 4
      tshirt_counts:
      - 2
      - 7
      - 6
      - 8
      - 7
      - 4
      - 7
      - 5
      - 5
      - 2
      - 5
      - 1
      - 4
      - 5
      - 7
      - 5
      - 1
      - 1
      - 4
      - 0
      - 8
      - 0
      - 7
      - 1
      - 4
      - 9
      - 0
      - 3
      - 9
      - 4
      - 5
      - 6
      - 2
      - 6
      - 8
      - 0
      - 6
      - 7
      - 8
      - 7
      - 6
      - 3
      - 8
      - 9
      - 8
      - 5
      - 7
      - 1
      - 1
      - 4
      - 1
      - 0
      - 4
      - 2
      - 8
      - 9
      - 1
      - 9
      - 4
      - 7
      - 6
      - 5
      - 8
      - 2
      - 9
      - 3
      - 9
      - 5
      - 5
      - 2
      - 9
      - 7
      - 3
      - 1
      - 9
      - 1
      - 3
      - 0
      - 7
      - 5
      - 4
      - 9
      - 8
      - 4
      - 1
      - 6
      - 7
      - 3
      - 4
      - 6
      - 7
      - 6
      - 1
      - 9
      - 1
      - 4
      - 3
      - 3
      - 4
      - 9
      - 3
      - 1
      - 3
      - 7
      - 2
      - 9
      - 4
      - 0
      - 1
      - 6
      - 9
      - 9
      - 9
      - 5
      - 2
      - 4
      - 9
      - 6
      - 6
      - 2
      - 5
      - 6
      - 2
      - 1
      - 4
      - 2
      - 0
      - 3
      - 3
      - 1
      - 2
      part1:
        ans1:
          value: '49.6'
          feedback: You got it!
        ans2:
          value: '24.8'
          feedback: Try again please!
        ans3:
          value: '61.6'
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