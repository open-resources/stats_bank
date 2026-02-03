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
      candidates: 1611
      stdev: 918500
      confidence: 95
      table: |-
        <table style="width:550px">
        <tr>
        <td>$1,320,600.0</td>
        <td>$1,420,100.0</td>
        <td>$1,558,900.0</td>
        <td>$101,400.0</td>
        <td>$1,109,700.0</td>
        </tr><tr>
        <td>$406,600.0</td>
        <td>$119,600.0</td>
        <td>$24,300.0</td>
        <td>$132,300.0</td>
        <td>$339,300.0</td>
        </tr><tr>
        <td>$1,122,800.0</td>
        <td>$469,500.0</td>
        <td>$770,300.0</td>
        <td>$1,490,500.0</td>
        <td>$1,953,900.0</td>
        </tr><tr>
        <td>$350,700.0</td>
        <td>$1,279,500.0</td>
        <td>$491,100.0</td>
        <td>$264,300.0</td>
        <td>$1,377,900.0</td>
        </tr><tr>
        <td>$378,100.0</td>
        <td>$84,100.0</td>
        <td>$650,700.0</td>
        <td>$2,039,300.0</td>
        <td>$772,500.0</td>
        </tr><tr>
        <td>$1,086,200.0</td>
        <td>$569,300.0</td>
        <td>$1,634,600.0</td>
        <td>$2,034,900.0</td>
        <td>$445,300.0</td>
        </tr><tr>
        <td>$816,400.0</td>
        <td>$1,238,800.0</td>
        <td>$929,600.0</td>
        <td>$1,310,600.0</td>
        <td>$327,600.0</td>
        </tr><tr>
        <td>$304,200.0</td>
        <td>$680,400.0</td>
        <td>$299,600.0</td>
        <td>$1,443,300.0</td>
        <td>$2,320,200.0</td>
        </tr>
        </table>
      part4:
        ans1:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 95% confidence that the mean amount of contributions received from all individuals by house candidates is between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Good job!
        ans2:
          value: |-
            <div class="mathjax_ignore">
            We estimate that 95% of all contributions received from all individuals by house candidates are between $(lower_bound) and $(upper_bound).
            </div>
          feedback: Try again please!
        ans3:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 95% confidence that the mean amount of contributions received from all individuals by House candidates is less than $(lower_bound).
            </div>
          feedback: Try again please!
        ans4:
          value: |-
            <div class="mathjax_ignore">
            We estimate with 95% confidence that the mean amount of contributions received from all individuals by House candidates is greater than $(upper_bound).
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