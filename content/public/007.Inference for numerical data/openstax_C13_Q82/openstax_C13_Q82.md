---
title: Silver Content of Byzantine Coinage
topic: Inference for numerical data
author: Gavin Kendal-Freedman
source: 13.2
template_version: 1.4
attribution: openstax-stats-2e
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 7.1.1.17
- 7.1.1.19
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
    weight: 9
part2:
  type: custom-input
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 9
    allow-blank: false
    label: $p = $
part4:
  type: multiple-choice
  pl-customizations:
    weight: 9
myst:
  substitutions:
    params:
      vars:
        title: Silver Content of Byzantine Coinage
      table: |-
        <table style="width:600px">
        <tr>
        <th>First Coinage</th>
        <th>Second Coinage</th>
        <th>Third Coinage</th>
        <th>Fourth Coinage</th>
        </tr><tr>
        <td>5.5</td>
        <td>10.4</td>
        <td>5.2</td>
        <td>6.1</td>
        </tr><tr>
        <td>6.8</td>
        <td>7.7</td>
        <td>4.6</td>
        <td>5.6</td>
        </tr><tr>
        <td>7.1</td>
        <td>7.8</td>
        <td>4.6</td>
        <td>5.7</td>
        </tr><tr>
        <td>6.8</td>
        <td>10.6</td>
        <td>5.0</td>
        <td>5.2</td>
        </tr><tr>
        <td>7.3</td>
        <td>7.9</td>
        <td>5.2</td>
        <td>5.5</td>
        </tr><tr>
        <td>6.6</td>
        <td>7.9</td>
        <td>4.8</td>
        <td>6.0</td>
        </tr><tr>
        <td>7.8</td>
        <td>9.8</td>
        <td>5.2</td>
        <td></td>
        </tr><tr>
        <td>7.3</td>
        <td></td>
        <td></td>
        <td></td>
        </tr><tr>
        <td>7.3</td>
        <td></td>
        <td></td>
        <td></td>
        </tr>
        </table>
      stats_table: |-
        <table style="width:600px">
        <tr>
        <th></th>
        <th>First Coinage</th>
        <th>Second Coinage</th>
        <th>Third Coinage</th>
        <th>Fourth Coinage</th>
        </tr><tr>
        <th>Mean</th>
        <td>$6.9444$</td>
        <td>$8.8714$</td>
        <td>$4.9429$</td>
        <td>$5.6833$</td>
        </tr><tr>
        <th>Variance</th>
        <td>$0.4228$</td>
        <td>$1.7657$</td>
        <td>$0.0762$</td>
        <td>$0.1097$</td>
        </tr>
        </table>
      first_sample: null
      second_sample: null
      third_sample: null
      fourth_sample: null
      means: null
      variances: null
      significance_level: 1
      first_len: 9
      second_len: 7
      third_len: 7
      fourth_len: 6
      part1:
        ans1:
          value: '$H_0: \forall i\ne j: \mu_i = \mu_j$ and $H_A: \exists i\ne j: \mu_i
            \ne \mu_j$'
          feedback: Good job!
        ans2:
          value: '$H_0: \forall i\ne j: \mu_i = \mu_j$ and $H_A: \forall i\ne j: \mu_i
            \ne \mu_j$'
          feedback: Try again!
        ans3:
          value: '$H_0: \forall i\ne j: \mu_i = \mu_j$ and $H_A: \mu_1 \ne \mu_2$'
          feedback: Try again!
        ans4:
          value: '$H_0: \forall i\ne j: \mu_i = \mu_j$ and $H_A: \mu_3 \ne \mu_4$'
          feedback: Try again!
        ans5:
          value: '$H_0: \exists i\ne j: \mu_i \ne \mu_j$ and $H_A: \forall i\ne j:
            \mu_i = \mu_j$'
          feedback: Try again!
        ans6:
          value: '$H_0: \forall i\ne j: \mu_i \ne \mu_j$ and $H_A: \forall i\ne j:
            \mu_i = \mu_j$'
          feedback: Try again!
      anova_table: |-
        <table style="width:800px">
        <tr>
        <th>Source of Variation</th>
        <th>Sum of Squares</th>
        <th>Degrees of Freedom</th>
        <th>Mean Square</th>
        <th>F Statistic</th>
        </tr><tr>
        <th>Between Groups</th>
        <td><pl-number-input answers-name="part2_between_ss_value" correct-answer="61.3235" show-help-text="false" size="10" display="block" comparison="decdig" digits="4" weight="1"></pl-number-input></td>
        <td><pl-integer-input answers-name="part2_between_df_value" correct-answer="3" show-help-text="false" size="10" display="block" weight="1"></pl-integer-input></td>
        <td><pl-number-input answers-name="part2_between_ms_value" correct-answer="20.4412" show-help-text="false" size="10" display="block" comparison="decdig" digits="4" weight="1"></pl-number-input></td>
        <td><pl-number-input answers-name="part2_between_f_value" correct-answer="34.1096" show-help-text="false" size="10" display="block" comparison="decdig" digits="4" weight="1"></pl-number-input></td>
        </tr><tr>
        <th>Within Groups</th>
        <td><pl-number-input answers-name="part2_within_ss_value" correct-answer="14.9820" show-help-text="false" size="10" display="block" comparison="decdig" digits="4" weight="1"></pl-number-input></td>
        <td><pl-integer-input answers-name="part2_within_df_value" correct-answer="25" show-help-text="false" size="10" display="block" weight="1"></pl-integer-input></td>
        <td><pl-number-input answers-name="part2_within_ms_value" correct-answer="0.5993" show-help-text="false" size="10" display="block" comparison="decdig" digits="4" weight="1"></pl-number-input></td>
        <td></td>
        </tr><tr>
        <th>Total</th>
        <td><pl-number-input answers-name="part2_total_ss_value" correct-answer="76.3055" show-help-text="false" size="10" display="block" comparison="decdig" digits="4" weight="1"></pl-number-input></td>
        <td><pl-integer-input answers-name="part2_total_df_value" correct-answer="28" show-help-text="false" size="10" display="block" weight="1"></pl-integer-input></td>
        <td></td>
        <td></td>
        </tr>
        </table>
      part4:
        ans1:
          value: Reject the null hypothesis because the p-value is less than 0.01
          feedback: Good Job
        ans2:
          value: Fail to reject the null hypothesis because the p-value is greater
            than 0.01
          feedback: Try again!
        ans3:
          value: Reject the null hypothesis because the p-value is greater than 0.01
          feedback: Try again
        ans4:
          value: Fail to reject the null hypothesis because the p-value is less than
            0.01
          feedback: Try again
---
# {{ params.vars.title }}
King Manuel I, Komnenus ruled the Byzantine Empire from Constantinople (Istanbul) during the years 1145 to 1180 A.D. The empire was very powerful during his reign, but declined significantly afterwards. Coins minted during his era were found in Cyprus, an island in the eastern Mediterranean Sea. {{ params.first_len }} coins were from his first coinage, {{ params.second_len }} from the second, {{ params.third_len }} from the third, and {{ params.fourth_len }} from a fourth. These spanned most of his reign. We have data on the silver content of the coins:

<style>
table:not([class]) {
  tr {
    border-bottom: 1px solid #ddd;
  }
  tr:hover {background-color: #D6EEEE;}
  th, td {
      padding: 10px;
      border-right: 2px solid #333; /* Vertical divider */
  }

  /* Remove the last column's right border */
  th:last-child, td:last-child {
      border-right: none;
  }
}
</style>

{{{ params.table }}}

Did the silver content of the coins change over the course of Manuel’s reign?

Here are the means and variances of each coinage. The data are unbalanced.

{{{ params.stats_table }}}

<pl-hidden-hints>
<pl-hint hint-name="Table as R code">
<pl-variable-output digits="3" show-mathematica="false" show-matlab="false" show-python="false" show-sympy="false">
  <pl-variable params-name="first_sample">first_sample</pl-variable>
  <pl-variable params-name="second_sample">second_sample</pl-variable>
  <pl-variable params-name="third_sample">third_sample</pl-variable>
  <pl-variable params-name="fourth_sample">fourth_sample</pl-variable>
  <pl-variable params-name="means">means</pl-variable>
  <pl-variable params-name="variances">variances</pl-variable>
</pl-variable-output>
</pl-hint>
</pl-hidden-hints>

## Part 1

Identify the null and alternative hypotheses.

### Answer Section

- {{ params.part1.ans1.value }}
- {{ params.part1.ans2.value }}
- {{ params.part1.ans3.value }}
- {{ params.part1.ans4.value }}
- {{ params.part1.ans5.value }}
- {{ params.part1.ans6.value }}

## Part 2

Complete the ANOVA table.

{{{ params.anova_table }}}

### Answer Section

## Part 3

Calculate the p-value for this test statistic. Please provide at least 4 decimal places of precision.

### Answer Section

Please enter a number.

## Part 4

What would your conclusion be, at a {{ params.significance_level }}% significance level?

### Answer Section

- {{ params.part4.ans1.value }}
- {{ params.part4.ans2.value }}
- {{ params.part4.ans3.value }}
- {{ params.part4.ans4.value }}

## Attribution

Problem is from the [OpenStax Introductory Statistics 2e](https://openstax.org/books/introductory-statistics-2e) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)