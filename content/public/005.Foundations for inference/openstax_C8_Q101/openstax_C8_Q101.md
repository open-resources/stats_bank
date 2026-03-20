---
title: Federal Election Donations
topic: Foundations for inference
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.7
- 5.1.1.8
- 5.1.1.11
- 5.1.1.12
- 5.1.1.13
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
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $\bar{x}= \$$
part2:
  type: integer-input
  pl-customizations:
    allow-blank: false
    label: $\text{Margin of Error}= \$$
part3:
  type: matrix-component-input
  pl-customizations:
    allow-fractions: true
    comparison: decdig
    digits: 0
    weight: 1
    allow-blank: false
    label: $\text{CI}=$
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
myst:
  substitutions:
    params:
      vars:
        title: Federal Election Donations
      candidates: 1610
      stdev: 916400
      confidence: 98
      table: |-
        <table style="width:550px">
        <tr>
        <td>$1,267,300.0</td>
        <td>$1,107,300.0</td>
        <td>$1,302,900.0</td>
        <td>$845,100.0</td>
        <td>$2,046,300.0</td>
        </tr><tr>
        <td>$363,800.0</td>
        <td>$1,291,800.0</td>
        <td>$213,400.0</td>
        <td>$1,029,700.0</td>
        <td>$641,500.0</td>
        </tr><tr>
        <td>$644,800.0</td>
        <td>$149,800.0</td>
        <td>$1,172,900.0</td>
        <td>$1,887,800.0</td>
        <td>$1,590,000.0</td>
        </tr><tr>
        <td>$568,900.0</td>
        <td>$819,900.0</td>
        <td>$59,800.0</td>
        <td>$82,300.0</td>
        <td>$439,000.0</td>
        </tr><tr>
        <td>$575,200.0</td>
        <td>$1,488,900.0</td>
        <td>$546,700.0</td>
        <td>$1,087,500.0</td>
        <td>$1,937,100.0</td>
        </tr><tr>
        <td>$357,200.0</td>
        <td>$992,800.0</td>
        <td>$360,400.0</td>
        <td>$31,300.0</td>
        <td>$1,434,400.0</td>
        </tr><tr>
        <td>$1,019,300.0</td>
        <td>$290,900.0</td>
        <td>$1,325,900.0</td>
        <td>$429,100.0</td>
        <td>$436,900.0</td>
        </tr><tr>
        <td>$273,600.0</td>
        <td>$969,400.0</td>
        <td>$1,017,000.0</td>
        <td>$670,200.0</td>
        <td>$773,900.0</td>
        </tr>
        </table>
      part4:
        ans1:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 98% confidence that the mean amount of contributions received from all individuals by house candidates is between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Good job!
        ans2:
          value: |-
            <div class="mathjax_ignore">
            We estimate that 98% of all contributions received from all individuals by house candidates are between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Try again please!
        ans3:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 98% confidence that the mean amount of contributions received from all individuals by House candidates is less than $(lower_bound).
            </div>
          feedback: Try again please!
        ans4:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 98% confidence that the mean amount of contributions received from all individuals by House candidates is greater than $(upper_bound).
            </div>
          feedback: Try again please!
---
# {{ params.vars.title }}
<div class="mathjax_ignore">
The Federal Election Commission collects information about campaign contributions and disbursements for candidates and political committees each election cycle. During a certain campaign season, there were {{ params.candidates }} candidates for the House of Representatives across the United States who received contributions from individuals. The table below shows the total receipts from individuals for a random selection of 40 House candidates rounded to the nearest $100.
</div>

The standard deviation for this data to the nearest hundred is $\sigma = {{ params.stdev }}$.

{{{ params.table }}}

## Part 1

Find the point estimate for the population mean.

### Answer Section

Please enter a numeric value in.

## Part 2

Using {{ params.confidence }}% confidence, calculate the margin of error.

### Answer Section

Please enter a numeric value in.

## Part 3

Create a {{ params.confidence }}% confidence interval for the mean total individual contributions.

### Answer Section

## Part 4

Interpret the confidence interval in the context of the problem.

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)