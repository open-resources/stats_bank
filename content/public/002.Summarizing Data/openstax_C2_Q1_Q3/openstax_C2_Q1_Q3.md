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
      description: The miles per gallon rating for 30 cars are shown below (lowest
        to highest).
      values:
      - '11'
      - '11'
      - '12'
      - '12'
      - '13'
      - '15'
      - '19'
      - '25'
      - '26'
      - '26'
      - '27'
      - '30'
      - '30'
      - '30'
      - '31'
      - '31'
      - '32'
      - '33'
      - '34'
      - '37'
      - '37'
      - '38'
      - '38'
      - '40'
      - '40'
      - '40'
      - '40'
      - '44'
      - '46'
      - '49'
      expected: |-
        1|1122359
        2|5667
        3|000112347788
        4|0000469
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