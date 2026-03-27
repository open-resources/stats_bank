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
    params:
      vars:
        title: Histograms
      sells:
        three: 18
        four: 5
        five: 17
        six: 16
        seven: 7
      headers:
      - Data Value (# cars)
      - Frequency
      - Relative Frequency
      - Cumulative Relative Frequency
      frequencies: &id001
      - 18
      - 5
      - 17
      - 16
      - 7
      sample_size: 63
      rel_freq: &id002
      - 0.2857142857142857
      - 0.07936507936507936
      - 0.2698412698412698
      - 0.25396825396825395
      - 0.1111111111111111
      cum_rel_freq: &id003
      - 0.2857142857142857
      - 0.36507936507936506
      - 0.6349206349206349
      - 0.8888888888888888
      - 1.0
      part1:
        table: |-
          <table style="width:100%">
          <tr>
          <th>Data Value (# cars)</th>
          <th>Frequency</th>
          <th>Relative Frequency</th>
          <th>Cumulative Relative Frequency</th>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row1_data_value" correct-answer="3" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row1_freq" correct-answer="18" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row1_rel_freq" correct-answer="0.2857" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row1_cum_rel_freq" correct-answer="0.2857" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row2_data_value" correct-answer="4" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row2_freq" correct-answer="5" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row2_rel_freq" correct-answer="0.0794" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row2_cum_rel_freq" correct-answer="0.3651" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row3_data_value" correct-answer="5" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row3_freq" correct-answer="17" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row3_rel_freq" correct-answer="0.2698" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row3_cum_rel_freq" correct-answer="0.6349" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row4_data_value" correct-answer="6" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row4_freq" correct-answer="16" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row4_rel_freq" correct-answer="0.2540" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row4_cum_rel_freq" correct-answer="0.8889" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row5_data_value" correct-answer="7" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row5_freq" correct-answer="7" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row5_rel_freq" correct-answer="0.1111" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row5_cum_rel_freq" correct-answer="1.0000" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr>
          </table>
      part4:
        ans1:
          value: The relative frequency shows the proportion of data points that have
            each value. The frequency tells the number of data points that have each
            value.
          feedback: Good Job!
        ans2:
          value: The relative frequency shows the number of data points that have
            each value. The frequency tells the proportion of data points that have
            each value.
          feedback: Not Quite - Check the definitions again.
        ans3:
          value: The relative frequency shows the proportion of data points that have
            each value or value less than the value. The frequency tells the number
            of data points that have each value or value less than the value.
          feedback: Not Quite - Check the definitions again.
        ans4:
          value: The relative frequency shows the number of data points that have
            each value or value less than the value. The frequency tells the proportion
            of data points that have each value or value less than the value.
          feedback: Not Quite - Check the definitions again.
      hist_values:
      - *id001
      - *id002
      - *id003
      - - 18
        - 23
        - 40
        - 56
        - 63
      part5:
        ans1:
          value: Histogram 1
          feedback: Good Job!
        ans2:
          value: Histogram 2
          feedback: Good Job!
        ans3:
          value: Histogram 3
          feedback: Try again!
        ans4:
          value: Histogram 4
          feedback: Try again!
---
# {{ params.vars.title }}
{{ params.sample_size }} randomly selected car salespersons were asked the number of cars they generally sell in one week. {{ params.sells.three }} people answered that they generally sell three cars; {{ params.sells.four }} generally sell four cars; {{ params.sells.five }} generally sell five cars; {{ params.sells.six }} generally sell six cars; {{ params.sells.seven }} generally sell seven cars.

## Part 1

Complete the table below:

{{{ params.part1.table }}}

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

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Part 5

Which of the following 4 plots is a correctly formed histogram for the data?

<pl-figure file-name="histograms.png" type="dynamic" width="500"></pl-figure>

### Answer Section

- {{ params.part5.ans1.value }}
- {{ params.part5.ans2.value }}
- {{ params.part5.ans3.value }}
- {{ params.part5.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)