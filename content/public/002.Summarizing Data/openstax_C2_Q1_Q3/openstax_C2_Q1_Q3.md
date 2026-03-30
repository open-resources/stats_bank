---
title: Stem and Leaf Plots
topic: Summarizing Data
author: Gavin Kendal-Freedman
source: 2.1
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 2.1.1.7
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
- GKF
part1:
  type: file-editor
  pl-customizations:
    file-name: stemplot.txt
myst:
  substitutions:
    params:
      vars:
        title: Stem and Leaf Plots
      description: The miles per gallon rating for 27 cars are shown below (lowest
        to highest).
      values:
      - '12'
      - '14'
      - '15'
      - '16'
      - '16'
      - '19'
      - '20'
      - '20'
      - '23'
      - '25'
      - '26'
      - '28'
      - '31'
      - '31'
      - '32'
      - '36'
      - '40'
      - '40'
      - '41'
      - '42'
      - '44'
      - '44'
      - '46'
      - '46'
      - '47'
      - '48'
      - '49'
      expected: |-
        1|245669
        2|003568
        3|1126
        4|00124466789
---
# {{ params.vars.title }}
{{ params.description }}

{{ params.values }}

## Part 1

Please create a stem plot of the values.

The example below shows what the expected stem plot would look like for the data $19,19,20,21,25,41$:

```
1|99
2|015
4|1
```

### Answer Section

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)