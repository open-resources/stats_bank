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
        <td>$12.325$</td>
        <td>$1.156$</td>
        <td>$10.659$</td>
        <td>$0.000$</td>
        </tr><tr>
        <th>poverty%</th>
        <td>$0.441$</td>
        <td>$0.059$</td>
        <td>$7.473$</td>
        <td>$0.000$</td>
        </tr>
        </table>
      graph:
        x:
        - 18.58813268277673
        - 16.02547856316889
        - 17.471744705246554
        - 20.172903315821976
        - 26.04394097331304
        - 22.657543975372818
        - 16.712391706743276
        - 8.4391296283559
        - 9.611628146644948
        - 17.117267920935852
        - 11.931741735906737
        - 20.042393661129072
        - 23.915474096068184
        - 21.027650876972988
        - 19.449662805568224
        - 15.404452030310882
        - 30.18815348714523
        - 18.891953614473664
        - 23.34749321974786
        - 20.897138522501553
        y:
        - 20.110074624921175
        - 17.790287724218448
        - 21.87800557364057
        - 21.293190118196847
        - 21.918390643898327
        - 24.020292317055134
        - 19.994935023129237
        - 14.864683886746601
        - 16.5120939255729
        - 19.16811241553475
        - 16.77954979201426
        - 22.305913179700774
        - 21.865200983932567
        - 24.057177031304875
        - 22.131833949922814
        - 20.448669497643184
        - 25.262092569476
        - 19.834452983923736
        - 20.563399328612654
        - 22.50680386878881
      part5:
        num1: 19
        num2: 21
        num3: 28
        num4: 2
        num5: 43
        num6: 3
        num7: 19
        num8: 2
        num9: 7
        num10: 17
        num11: 26
        num12: 6
        num13: 19
        num14: 22
        num15: 21
        num16: 26
        num17: 21
        num18: 36
        num19: 2
        num20: 22
        num21: 26
      description:
        num1: 19
        num2: 12.325
        num3: 1.156
        num4: 10.659
        num5: 0.0
        num6: 0.441
        num7: 0.059
        num8: 7.473
        num9: 0.0
        num10: 1.352
        num11: 75.63
        num12: 74.27
      part2:
        ans1:
          value: The value is meaningless
          feedback: Correct! Nice work
        ans2:
          value: The expected murder rate in metropolitan areas with no poverty is
            12.325.
          feedback: Correct! Nice work
        ans3:
          value: The expected murder rate in metropolitan areas with no poverty is
            0.441.
          feedback: Not quite - think about what the value represents.
        ans4:
          value: The expected murder rate in metropolitan areas with no poverty is
            -12.325.
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
          value: Poverty level explains $75.63\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Correct! Nice work
        ans2:
          value: Poverty level explains $86.96\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Not Quite. Please Try Again!
        ans3:
          value: Poverty level explains $74.27\%$ of the variability in murder rates
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