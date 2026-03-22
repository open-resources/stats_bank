---
title: Chi Squared Choices
topic: Inference for categorical data
author: Gavin Kendal-Freedman
source: 11
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 6.1.1.9
- 6.1.1.15
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
assets: null
part1:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part2:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
    order: fixed
myst:
  substitutions:
    params:
      vars:
        title: Chi Squared Choices
      scenario1: A math teacher wants to see if two of their classes have the same
        distribution of test scores.
      part1:
        ans1:
          value: A chi-squared goodness of fit test
          feedback: This is incorrect. A chi-squared goodness of fit test is used
            to compare an observed distribution to an expected distribution for a
            single categorical variable.
        ans2:
          value: A chi-squared test of independence
          feedback: This is incorrect. A chi-squared test of independence is used
            to determine if there is an association between two categorical variables.
        ans3:
          value: A chi-squared test of homogeneity
          feedback: Good Job!
        ans4:
          value: None of the above
          feedback: This is incorrect.
      scenario2: An economist is deriving a model to predict outcomes on the stock
        market. They create a list of expected points on the stock market index for
        the next two weeks. At the close of each day’s trading, The economist records
        the actual points on the index. They want to see how well the model matched
        what actually happened.
      part2:
        ans1:
          value: A chi-squared goodness of fit test
          feedback: Good Job!
        ans2:
          value: A chi-squared test of independence
          feedback: This is incorrect. A chi-squared test of independence is used
            to determine if there is an association between two categorical variables.
        ans3:
          value: A chi-squared test of homogeneity
          feedback: This is incorrect. A chi-squared test of homogeneity is used to
            determine if different populations have the same distribution of a categorical
            variable.
        ans4:
          value: None of the above
          feedback: This is incorrect.
      scenario3: An archeologist is calculating the distribution of the frequency
        of the number of artifacts they find in a dig site. Based on previous digs,
        the archeologist creates an expected distribution broken down by grid sections
        in the dig site. Once the site has been fully excavated, they compare the
        actual number of artifacts found in each grid section to see if their expectation
        was accurate.
      part3:
        ans1:
          value: A chi-squared goodness of fit test
          feedback: Good Job!
        ans2:
          value: A chi-squared test of independence
          feedback: This is incorrect. A chi-squared test of independence is used
            to determine if there is an association between two categorical variables.
        ans3:
          value: A chi-squared test of homogeneity
          feedback: This is incorrect. A chi-squared test of homogeneity is used to
            determine if different populations have the same distribution of a categorical
            variable.
        ans4:
          value: None of the above
          feedback: This is incorrect.
---
# {{ params.vars.title }}
For each of the following 3 scenarios, identify which type of chi-squared test would be most appropriate to use.

## Part 1

{{ params.scenario1 }}

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}

## Part 2

{{ params.scenario2 }}

### Answer Section

- {{ params.part2.ans1.value }}
- {{ params.part2.ans2.value }}
- {{ params.part2.ans3.value }}
- {{ params.part2.ans4.value }}

## Part 3

{{ params.scenario3 }}

### Answer Section

- {{ params.part3.ans1.value }}
- {{ params.part3.ans2.value }}
- {{ params.part3.ans3.value }}
- {{ params.part3.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)