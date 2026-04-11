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
      candidates: 1636
      stdev: 903500
      confidence: 99
      table: |-
        <table style="width:550px">
        <tr>
        <td>$145,300.0</td>
        <td>$219,400.0</td>
        <td>$843,300.0</td>
        <td>$1,722,000.0</td>
        <td>$157,400.0</td>
        </tr><tr>
        <td>$1,038,100.0</td>
        <td>$676,300.0</td>
        <td>$1,117,900.0</td>
        <td>$137,900.0</td>
        <td>$183,300.0</td>
        </tr><tr>
        <td>$788,500.0</td>
        <td>$454,900.0</td>
        <td>$71,600.0</td>
        <td>$554,200.0</td>
        <td>$350,300.0</td>
        </tr><tr>
        <td>$199,500.0</td>
        <td>$335,500.0</td>
        <td>$982,600.0</td>
        <td>$1,337,800.0</td>
        <td>$109,200.0</td>
        </tr><tr>
        <td>$886,700.0</td>
        <td>$725,100.0</td>
        <td>$31,600.0</td>
        <td>$1,301,000.0</td>
        <td>$2,084,700.0</td>
        </tr><tr>
        <td>$1,994,300.0</td>
        <td>$43,000.0</td>
        <td>$258,500.0</td>
        <td>$96,300.0</td>
        <td>$776,100.0</td>
        </tr><tr>
        <td>$1,254,500.0</td>
        <td>$236,400.0</td>
        <td>$481,400.0</td>
        <td>$320,200.0</td>
        <td>$837,100.0</td>
        </tr><tr>
        <td>$949,900.0</td>
        <td>$1,494,000.0</td>
        <td>$1,491,900.0</td>
        <td>$863,000.0</td>
        <td>$1,294,300.0</td>
        </tr>
        </table>
      part4:
        ans1:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 99% confidence that the mean amount of contributions received from all individuals by house candidates is between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Good job!
        ans2:
          value: |-
            <div class="mathjax_ignore">
            We estimate that 99% of all contributions received from all individuals by house candidates are between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Try again please!
        ans3:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 99% confidence that the mean amount of contributions received from all individuals by House candidates is less than $(lower_bound).
            </div>
          feedback: Try again please!
        ans4:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 99% confidence that the mean amount of contributions received from all individuals by House candidates is greater than $(upper_bound).
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