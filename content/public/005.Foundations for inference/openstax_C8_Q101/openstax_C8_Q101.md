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
      candidates: 1557
      stdev: 907100
      confidence: 90
      table: |-
        <table style="width:550px">
        <tr>
        <td>$5,200.0</td>
        <td>$2,168,800.0</td>
        <td>$384,400.0</td>
        <td>$411,700.0</td>
        <td>$468,600.0</td>
        </tr><tr>
        <td>$837,400.0</td>
        <td>$1,918,300.0</td>
        <td>$564,300.0</td>
        <td>$1,067,900.0</td>
        <td>$873,600.0</td>
        </tr><tr>
        <td>$711,800.0</td>
        <td>$919,100.0</td>
        <td>$167,100.0</td>
        <td>$1,339,800.0</td>
        <td>$882,300.0</td>
        </tr><tr>
        <td>$237,400.0</td>
        <td>$152,100.0</td>
        <td>$425,000.0</td>
        <td>$1,736,100.0</td>
        <td>$387,500.0</td>
        </tr><tr>
        <td>$493,900.0</td>
        <td>$988,000.0</td>
        <td>$383,900.0</td>
        <td>$1,192,600.0</td>
        <td>$1,167,500.0</td>
        </tr><tr>
        <td>$910,800.0</td>
        <td>$1,764,800.0</td>
        <td>$2,150,400.0</td>
        <td>$811,300.0</td>
        <td>$853,800.0</td>
        </tr><tr>
        <td>$677,000.0</td>
        <td>$182,500.0</td>
        <td>$1,820,500.0</td>
        <td>$1,259,200.0</td>
        <td>$56,500.0</td>
        </tr><tr>
        <td>$262,000.0</td>
        <td>$601,600.0</td>
        <td>$1,044,900.0</td>
        <td>$2,748,200.0</td>
        <td>$129,800.0</td>
        </tr>
        </table>
      part4:
        ans1:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 90% confidence that the mean amount of contributions received from all individuals by house candidates is between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Good job!
        ans2:
          value: |-
            <div class="mathjax_ignore">
            We estimate that 90% of all contributions received from all individuals by house candidates are between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Try again please!
        ans3:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 90% confidence that the mean amount of contributions received from all individuals by House candidates is less than $(lower_bound).
            </div>
          feedback: Try again please!
        ans4:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 90% confidence that the mean amount of contributions received from all individuals by House candidates is greater than $(upper_bound).
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