---
title: Histograms
topic: Summarizing Data
author: Gavin Kendal-Freedman
source: 2.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: true
showCorrectAnswer: false
outcomes:
- 2.1.1.4
difficulty:
- easy
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
- autograder
assets: null
part1:
  type: custom-input
part2:
  type: number-input
  pl-customizations:
    weight: 10
    comparison: decdig
    digits: 2
part3:
  type: number-input
  pl-customizations:
    weight: 10
    comparison: decdig
    digits: 2
part4:
  type: multiple-choice
  pl-customizations:
    weight: 10
part5:
  type: checkbox
  pl-customizations:
    weight: 10
    partial-credit: true
    partial-credit-method: EDC
    hide-letter-keys: true
    fixed-order: true
myst:
  substitutions:
    params_vars_title: Histograms
    params_sells_three: 14
    params_sells_four: 14
    params_sells_five: 15
    params_sells_six: 17
    params_sells_seven: 13
    params_headers:
    - Data Value (# cars)
    - Frequency
    - Relative Frequency
    - Cumulative Relative Frequency
    params_frequencies: &id002
    - 14
    - 14
    - 15
    - 17
    - 13
    params_sample_size: 73
    params_rel_freq: &id001
    - 0.1917808219178082
    - 0.1917808219178082
    - 0.2054794520547945
    - 0.2328767123287671
    - 0.1780821917808219
    params_cum_rel_freq: &id003
    - 0.1917808219178082
    - 0.3835616438356164
    - 0.5890410958904109
    - 0.821917808219178
    - 1.0
    params_part1_table: |-
      <table style="width:100%">
      <tr>
      <th>Data Value (# cars)</th>
      <th>Frequency</th>
      <th>Relative Frequency</th>
      <th>Cumulative Relative Frequency</th>
      </tr><tr>
      <td><pl-integer-input answers-name="part1_row1_data_value" correct-answer="3" show-help-text="false" size="10" display="block"></pl-integer-input></td>
      <td><pl-integer-input answers-name="part1_row1_freq" correct-answer="14" show-help-text="false" size="5" display="block"></pl-integer-input></td>
      <td><pl-number-input answers-name="part1_row1_rel_freq" correct-answer="0.1918" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      <td><pl-number-input answers-name="part1_row1_cum_rel_freq" correct-answer="0.1918" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      </tr><tr>
      <td><pl-integer-input answers-name="part1_row2_data_value" correct-answer="4" show-help-text="false" size="10" display="block"></pl-integer-input></td>
      <td><pl-integer-input answers-name="part1_row2_freq" correct-answer="14" show-help-text="false" size="5" display="block"></pl-integer-input></td>
      <td><pl-number-input answers-name="part1_row2_rel_freq" correct-answer="0.1918" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      <td><pl-number-input answers-name="part1_row2_cum_rel_freq" correct-answer="0.3836" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      </tr><tr>
      <td><pl-integer-input answers-name="part1_row3_data_value" correct-answer="5" show-help-text="false" size="10" display="block"></pl-integer-input></td>
      <td><pl-integer-input answers-name="part1_row3_freq" correct-answer="15" show-help-text="false" size="5" display="block"></pl-integer-input></td>
      <td><pl-number-input answers-name="part1_row3_rel_freq" correct-answer="0.2055" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      <td><pl-number-input answers-name="part1_row3_cum_rel_freq" correct-answer="0.5890" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      </tr><tr>
      <td><pl-integer-input answers-name="part1_row4_data_value" correct-answer="6" show-help-text="false" size="10" display="block"></pl-integer-input></td>
      <td><pl-integer-input answers-name="part1_row4_freq" correct-answer="17" show-help-text="false" size="5" display="block"></pl-integer-input></td>
      <td><pl-number-input answers-name="part1_row4_rel_freq" correct-answer="0.2329" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      <td><pl-number-input answers-name="part1_row4_cum_rel_freq" correct-answer="0.8219" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      </tr><tr>
      <td><pl-integer-input answers-name="part1_row5_data_value" correct-answer="7" show-help-text="false" size="10" display="block"></pl-integer-input></td>
      <td><pl-integer-input answers-name="part1_row5_freq" correct-answer="13" show-help-text="false" size="5" display="block"></pl-integer-input></td>
      <td><pl-number-input answers-name="part1_row5_rel_freq" correct-answer="0.1781" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      <td><pl-number-input answers-name="part1_row5_cum_rel_freq" correct-answer="1.0000" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
      </tr>
      </table>
    params_part4_ans1_value: The relative frequency shows the proportion of data points
      that have each value. The frequency tells the number of data points that have
      each value.
    params_part4_ans1_feedback: Good Job!
    params_part4_ans2_value: The relative frequency shows the number of data points
      that have each value. The frequency tells the proportion of data points that
      have each value.
    params_part4_ans2_feedback: Not Quite - Check the definitions again.
    params_part4_ans3_value: The relative frequency shows the proportion of data points
      that have each value or value less than the value. The frequency tells the number
      of data points that have each value or value less than the value.
    params_part4_ans3_feedback: Not Quite - Check the definitions again.
    params_part4_ans4_value: The relative frequency shows the number of data points
      that have each value or value less than the value. The frequency tells the proportion
      of data points that have each value or value less than the value.
    params_part4_ans4_feedback: Not Quite - Check the definitions again.
    params_hist_values:
    - *id001
    - - 14
      - 28
      - 43
      - 60
      - 73
    - *id002
    - *id003
    params_part5_ans1_value: Histogram 1
    params_part5_ans1_feedback: Good Job!
    params_part5_ans2_value: Histogram 2
    params_part5_ans2_feedback: Try again!
    params_part5_ans3_value: Histogram 3
    params_part5_ans3_feedback: Good Job!
    params_part5_ans4_value: Histogram 4
    params_part5_ans4_feedback: Try again!
---
# {{ params_vars_title }}
{{ params.sample_size }} randomly selected car salespersons were asked the number of cars they generally sell in one week. {{ params_sells_three }} people answered that they generally sell three cars; {{ params_sells_four }} generally sell four cars; {{ params_sells_five }} generally sell five cars; {{ params_sells_six }} generally sell six cars; {{ params_sells_seven }} generally sell seven cars.

## Part 1

Complete the table below:

{{{ params_part1_table }}}

### Answer Section

## Part 2

What does the frequency column in the Table in Part 1 sum to?

### Answer Section

## Part 3

What does the relative frequency column in the Table in Part 1 sum to?

### Answer Section

## Part 4

What is the difference between relative frequency and frequency for each data value in the Table in Part 1?

### Answer Section

- {{ params_part4_ans1_value }}
- {{ params_part4_ans2_value }}
- {{ params_part4_ans3_value }}
- {{ params_part4_ans4_value }}

## Part 5

Which of the following 4 plots is a correctly formed histogram for the data?

<pl-figure file-name="histograms.png" type="dynamic" width="500"></pl-figure>

### Answer Section

- {{ params_part5_ans1_value }}
- {{ params_part5_ans2_value }}
- {{ params_part5_ans3_value }}
- {{ params_part5_ans4_value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)