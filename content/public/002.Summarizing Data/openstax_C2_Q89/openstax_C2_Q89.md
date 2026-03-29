---
title: Age of purchasing BMW boxplot
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
- 2.1.1.5
- 2.1.1.8
- 2.1.1.11
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
  type: multiple-choice
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
    order: fixed
part5:
  type: integer-input
  pl-customizations:
    weight: 1
    allow-blank: false
    label: Spread $\approx$
    suffix: years
    atol: 1
part6:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part7:
  type: number-input
  pl-customizations:
    atol: 1
    weight: 1
    allow-blank: false
    label: Spread $\approx$
    suffix: years
part8:
  type: number-input
  pl-customizations:
    atol: 1
    weight: 1
    allow-blank: false
    label: IQR$\approx$
    suffix: years
part9:
  type: multiple-choice
  pl-customizations:
    weight: 1
part10:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Age of purchasing BMW boxplot
      chosen_series: '7'
      quantiles1:
      - 18
      - 29
      - 36
      - 41
      - 64
      quantiles2:
      - 32
      - 40
      - 41
      - 54
      - 62
      quantiles3:
      - 34
      - 42
      - 48
      - 57
      - 68
      part1:
        ans1:
          value: Each box plot is symmetrical, showing that the ages of the top 50%
            of buyers are evenly distributed as the ages of the lower 50%.
          feedback: Try again please!
        ans2:
          value: Each box plot is more clustered in the lower values. Each plot is
            skewed to the left, so the ages of the top 50% of buyers are less variable
            than the ages of the lower 50%.
          feedback: Try again please!
        ans3:
          value: Each box plot is spread out more in the greater values. Each plot
            is skewed to the left, so the ages of the top 50% of buyers are more variable
            than the ages of the lower 50%.
          feedback: Try again please!
        ans4:
          value: Each box plot is spread out more in the greater values. Each plot
            is skewed to the right, so the ages of the top 50% of buyers are more
            variable than the ages of the lower 50%.
          feedback: Correct!
      part2:
        ans1:
          value: BMW 5 series
          feedback: Which has the longest whisker?
        ans2:
          value: BMW 7 series
          feedback: Which has the longest whisker?
        ans3:
          value: BMW 3 series
          feedback: Correct!
      part3:
        ans1:
          value: Comparing the median ages, younger people tend to buy the BMW 3 series,
            while older people tend to buy the BMW 5 series. This is a rule, because
            there is little variability in each data set.
          feedback: Try again please!
        ans2:
          value: Comparing the median ages, younger people tend to buy the BMW 7 series,
            while older people tend to buy the BMW 3 series. However, this is not
            a rule, because there is so much variability in each data set.
          feedback: Try again please!
        ans3:
          value: Comparing the median ages, younger people tend to buy the BMW 3 series,
            while older people tend to buy the BMW 7 series. However, this is not
            a rule, because there is so much variability in each data set.
          feedback: Correct!
      part4:
        ans1:
          value: the first quarter
          feedback: Try again please!
        ans2:
          value: the second quarter
          feedback: Correct!
        ans3:
          value: the third quarter
          feedback: Try again please!
        ans4:
          value: the fourth quarter
          feedback: Try again please!
      part6:
        ans1:
          value: the first quarter
          feedback: Try again please!
        ans2:
          value: the second quarter
          feedback: Try again please!
        ans3:
          value: the third quarter
          feedback: Try again please!
        ans4:
          value: the fourth quarter
          feedback: Correct!
      part9:
        ans1:
          value: There are more data in the interval 31 to 38.
          feedback: Try again please!
        ans2:
          value: There are more data in the interval 45 to 55.
          feedback: Try again please!
        ans3:
          value: There is not enough information to tell. Each interval lies within
            a quarter, so we cannot tell exactly where the data in that quarter is
            concentrated.
          feedback: Correct!
        ans4:
          value: There is the same amount of data in both intervals.
          feedback: Try again please!
      part10:
        ans1:
          value: 42-48
          feedback: Try again please!
        ans2:
          value: 48-60
          feedback: Try again please!
        ans3:
          value: 37-41
          feedback: Correct!
---
# {{ params.vars.title }}
A survey was conducted of 130 purchasers of new BMW 3 series cars, 130 purchasers of new BMW 5 series cars, and 130 purchasers of new BMW 7 series cars. In it, people were asked the age they were when they purchased their car. The following box plots display the results.

<pl-figure file-name="figure 1.png" type="dynamic" width="500px"></pl-figure>

3: BMW 7 series

2: BMW 5 series

1: BMW 3 series

## Part 1

Describe what the shape of each box plot implies about the distribution of the data collected for that car series.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

Which group is most likely to have an outlier?

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}

## Part 3

Compare the three box plots. What do they imply about the age of purchasing a BMW from the series when compared to each other?

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}

## Part 4

Look at the BMW {{ params.chosen_series }} series. Which quarter has the smallest spread of data?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

What is the spread in the previous question?

### Answer Section

Please enter a numeric value in.

## Part 6

Look at the BMW {{ params.chosen_series }} series. Which quarter has the largest spread of data?

### Answer Section

- {{ params.part6.ans1.value }}
- {{ params.part6.ans2.value }}
- {{ params.part6.ans3.value }}
- {{ params.part6.ans4.value }}

## Part 7

What is the spread in the previous question?

### Answer Section

Please enter a numeric value in.

## Part 8

Look at the BMW {{ params.chosen_series }} series. Estimate the interquartile range (IQR).

### Answer Section

Please enter a numeric value in.

## Part 9

Look at the BMW {{ params.chosen_series }} series. Are there more data in the interval 31 to 38 or in the interval 45 to 55? How do you know this?

### Answer Section

- {{ params.part9.ans1.value }}
- {{ params.part9.ans2.value }}
- {{ params.part9.ans3.value }}

## Part 10

Look at the BMW {{ params.chosen_series }} series. Which interval has the fewest data in it?

### Answer Section

- {{ params.part10.ans1.value }}
- {{ params.part10.ans2.value }}
- {{ params.part10.ans3.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)