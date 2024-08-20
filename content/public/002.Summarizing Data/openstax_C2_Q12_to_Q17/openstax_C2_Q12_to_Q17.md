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
        three: 7
        four: 19
        five: 20
        six: 13
        seven: 13
      headers:
      - Data Value (# cars)
      - Frequency
      - Relative Frequency
      - Cumulative Relative Frequency
      frequencies: &id003
      - 7
      - 19
      - 20
      - 13
      - 13
      sample_size: 72
      rel_freq: &id002
      - 0.09722222222222222
      - 0.2638888888888889
      - 0.2777777777777778
      - 0.18055555555555555
      - 0.18055555555555555
      cum_rel_freq: &id001
      - 0.09722222222222222
      - 0.3611111111111111
      - 0.6388888888888888
      - 0.8194444444444444
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
          <td><pl-integer-input answers-name="part1_row1_freq" correct-answer="7" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row1_rel_freq" correct-answer="0.0972" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row1_cum_rel_freq" correct-answer="0.0972" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row2_data_value" correct-answer="4" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row2_freq" correct-answer="19" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row2_rel_freq" correct-answer="0.2639" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row2_cum_rel_freq" correct-answer="0.3611" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row3_data_value" correct-answer="5" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row3_freq" correct-answer="20" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row3_rel_freq" correct-answer="0.2778" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row3_cum_rel_freq" correct-answer="0.6389" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row4_data_value" correct-answer="6" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row4_freq" correct-answer="13" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row4_rel_freq" correct-answer="0.1806" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          <td><pl-number-input answers-name="part1_row4_cum_rel_freq" correct-answer="0.8194" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
          </tr><tr>
          <td><pl-integer-input answers-name="part1_row5_data_value" correct-answer="7" show-help-text="false" size="10" display="block"></pl-integer-input></td>
          <td><pl-integer-input answers-name="part1_row5_freq" correct-answer="13" show-help-text="false" size="5" display="block"></pl-integer-input></td>
          <td><pl-number-input answers-name="part1_row5_rel_freq" correct-answer="0.1806" show-help-text="false" comparison="decdig" size="25" display="block" digits="4"></pl-number-input></td>
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
      - - 7
        - 26
        - 46
        - 59
        - 72
      part5:
        ans1:
          value: Histogram 1
          feedback: Try again!
        ans2:
          value: Histogram 2
          feedback: Good Job!
        ans3:
          value: Histogram 3
          feedback: Good Job!
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