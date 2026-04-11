---
title: Murders and poverty, Part I
topic: Introduction to linear regression
author: Gavin Kendal-Freedman
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
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
        <td>$14.921$</td>
        <td>$0.842$</td>
        <td>$17.725$</td>
        <td>$0.000$</td>
        </tr><tr>
        <th>poverty%</th>
        <td>$0.386$</td>
        <td>$0.050$</td>
        <td>$7.790$</td>
        <td>$0.000$</td>
        </tr>
        </table>
      graph:
        x:
        - 22.420573343556683
        - 15.356536804386227
        - 11.051272209702272
        - 23.272684052812785
        - 23.16164928859918
        - 11.215030656162464
        - 17.053925988500108
        - 9.948350230071426
        - 15.319244557438104
        - 16.74290000320448
        - 12.510083808198791
        - 11.86964746172276
        - 9.846712263299839
        - 29.44216204940582
        - 16.878603023037105
        - 20.579459238483977
        - 19.76770475277627
        - 11.632601342945243
        - 5.827539008018569
        - 16.598811009210486
        y:
        - 23.1427548543744
        - 18.529191257652794
        - 20.543033786260484
        - 23.811004495866086
        - 25.34425595805479
        - 18.85263931518072
        - 20.17671539801697
        - 18.032902307633638
        - 20.679681775514283
        - 21.427400152386923
        - 22.64392130335396
        - 19.25561679257629
        - 17.81151653688504
        - 25.745042779632463
        - 21.310028431898
        - 22.045789379185123
        - 22.97804139120336
        - 19.392892764683804
        - 16.728869468264108
        - 23.673930393445605
      part5:
        num1: 21
        num2: 26
        num3: 24
        num4: 8
        num5: 41
        num6: 8
        num7: 19
        num8: 8
        num9: 26
        num10: 16
        num11: 23
        num12: 15
        num13: 19
        num14: 22
        num15: 26
        num16: 23
        num17: 22
        num18: 37
        num19: 8
        num20: 22
        num21: 23
      description:
        num1: 21
        num2: 14.921
        num3: 0.842
        num4: 17.725
        num5: 0.0
        num6: 0.386
        num7: 0.05
        num8: 7.79
        num9: 0.0
        num10: 1.252
        num11: 77.13
        num12: 75.85
      part2:
        ans1:
          value: The value is meaningless
          feedback: Correct! Nice work
        ans2:
          value: The expected murder rate in metropolitan areas with no poverty is
            14.921.
          feedback: Correct! Nice work
        ans3:
          value: The expected murder rate in metropolitan areas with no poverty is
            0.386.
          feedback: Not quite - think about what the value represents.
        ans4:
          value: The expected murder rate in metropolitan areas with no poverty is
            -14.921.
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
          value: Poverty level explains $77.13\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Correct! Nice work
        ans2:
          value: Poverty level explains $87.82\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Not Quite. Please Try Again!
        ans3:
          value: Poverty level explains $75.85\%$ of the variability in murder rates
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