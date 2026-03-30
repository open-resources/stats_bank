---
title: Murders and poverty, Part I
topic: Introduction to linear regression
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 8.1.1.14
- 8.1.1.16
- 8.1.1.17
- 8.1.1.19
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
  type: matrix-component-input
  pl-customizations:
    weight: 1
    allow-fractions: 'true'
    allow-blank: false
    label: $Model = $
part2:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
    partial-credit-method: EDC
part3:
  type: multiple-choice
  pl-customizations:
    weight: 1
    fixed-order: true
part4:
  type: multiple-choice
  pl-customizations:
    weight: 1
part5:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 2
    weight: 1
    allow-blank: true
    label: $d= $
myst:
  substitutions:
    params:
      vars:
        title: Murders and poverty, Part I
      table1: |-
        <table style="width:75%">
        <tr>
        <th></th>
        <th>Estimate</th>
        <th>Std. Error</th>
        <th>t value</th>
        <th>Pr(>|t|)</th>
        </tr><tr>
        <th>(Intercept)</th>
        <td>$12.822$</td>
        <td>$0.986$</td>
        <td>$12.997$</td>
        <td>$0.000$</td>
        </tr><tr>
        <th>poverty%</th>
        <td>$0.532$</td>
        <td>$0.062$</td>
        <td>$8.529$</td>
        <td>$0.000$</td>
        </tr>
        </table>
      graph:
        x:
        - 9.321615258635566
        - 21.227836049798466
        - 20.86864625395971
        - 8.900748268815445
        - 17.794549968813875
        - 12.396512309608198
        - 12.753511988194608
        - 26.960278281294386
        - 8.50932156599118
        - 12.471430434164137
        - 17.134363625695137
        - 22.33991496462822
        - 19.427229782485977
        - 9.369663771404603
        - 22.101707332005326
        - 6.498378674343677
        - 5.716621626803425
        - 13.749869367923576
        - 14.59018963824539
        - 11.915337873508255
        y:
        - 15.204151273254379
        - 22.88803762085437
        - 23.58196205798365
        - 16.20728636070673
        - 22.96988919167269
        - 19.121209125880362
        - 18.947195952670008
        - 29.716854384418234
        - 16.067707172468587
        - 20.65748608151181
        - 20.924212727928992
        - 23.656781383769992
        - 21.435773616790186
        - 19.47885935835415
        - 26.141269062961086
        - 19.80443362940018
        - 16.8449191213762
        - 21.35998790266914
        - 19.55894848857026
        - 18.265154126722667
      part5:
        num1: 20
        num2: 18
        num3: 28
        num4: 4
        num5: 37
        num6: 6
        num7: 18
        num8: 4
        num9: 10
        num10: 18
        num11: 26
        num12: 4
        num13: 18
        num14: 23
        num15: 18
        num16: 26
        num17: 23
        num18: 34
        num19: 4
        num20: 23
        num21: 26
      description:
        num1: 20
        num2: 12.822
        num3: 0.986
        num4: 12.997
        num5: 0.0
        num6: 0.532
        num7: 0.062
        num8: 8.529
        num9: 0.0
        num10: 1.628
        num11: 80.16
        num12: 79.06
      part2:
        ans1:
          value: The value is meaningless
          feedback: Correct! Nice work
        ans2:
          value: The expected murder rate in metropolitan areas with no poverty is
            12.822.
          feedback: Correct! Nice work
        ans3:
          value: The expected murder rate in metropolitan areas with no poverty is
            0.532.
          feedback: Not quite - think about what the value represents.
        ans4:
          value: The expected murder rate in metropolitan areas with no poverty is
            -12.822.
          feedback: Not quite - check what value is being used.
      part3:
        ans1:
          value: 'True'
          feedback: Correct! Nice work
        ans2:
          value: 'False'
          feedback: Incorrect - this interpretation of the slope is correct.
      part4:
        ans1:
          value: Poverty level explains $80.16\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Correct! Nice work
        ans2:
          value: Poverty level explains $89.53\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Not Quite. Please Try Again!
        ans3:
          value: Poverty level explains $79.06\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Not Quite. Please Try Again!
---
# {{ params.vars.title }}
The following regression output is for predicting annual murders per million from percentage living in poverty in a random sample of ${{ params.description.num1 }}$ metropolitan areas.

{{{ params.table1 }}}

$s = ${{ params.description.num10 }} $R^2 = ${{ params.description.num11 }}$\%$ $R^2\_{adj} = ${{ params.description.num12 }}$\%$

<pl-figure file-name="murders_poverty.png" type="dynamic" width=50% alt="A scatterplot is shown with ${{ params.part5.num1 }}$ points. The horizontal axis is 'Percent in Poverty' and has values ranging from ${{ params.part5.num2 }}$\% to ${{ params.part5.num3 }}$\%. The vertical axis is 'Annual Murders per Million' with values ranging from about ${{ params.part5.num4 }}$ to ${{ params.part5.num5 }}$. There are ${{ params.part5.num6 }}$ points with poverty below ${{ params.part5.num7 }}$\%, and the Murder Rate for these values ranges from ${{ params.part5.num8 }}$ to ${{ params.part5.num9 }}$, with one exception of a point at about ${{ params.part5.num10 }}$\% with a murder rate of about ${{ params.part5.num11 }}$. There are ${{ params.part5.num12 }}$ points with a poverty rate of ${{ params.part5.num13 }}$\% to ${{ params.part5.num14 }}$\%, and the murder rate for these points largely range from ${{ params.part5.num15 }}$ to ${{ params.part5.num16 }}$, with one exception of a point at about ${{ params.part5.num17 }}$\% poverty and a murder rate of ${{ params.part5.num18 }}$. There are ${{ params.part5.num19 }}$ points where poverty is larger than ${{ params.part5.num20 }}$\%, and these have murder rates ranging from ${{ params.part5.num21 }}$ to 40.">

## Part 1

Write out the linear model. Enter the intercept and slope into the matrix below in that order (`[intercept, slope]`)

### Answer Section

## Part 2

Interpret the intercept.

### Answer Section

## Part 3

True or False: A correct interpretation of the slope is that for each additional percentage increase in poverty, we expect murders per million to be higher on average by ${{ params.description.num6 }}$.

### Answer Section

## Part 4

Interpret $R^2$.

### Answer Section

## Part 5

Calculate the correlation coefficient.

### Answer Section

Please enter a numeric value in.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)