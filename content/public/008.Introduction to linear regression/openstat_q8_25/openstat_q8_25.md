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
        <td>$5.696$</td>
        <td>$1.404$</td>
        <td>$4.058$</td>
        <td>$0.001$</td>
        </tr><tr>
        <th>poverty%</th>
        <td>$0.415$</td>
        <td>$0.040$</td>
        <td>$10.303$</td>
        <td>$0.000$</td>
        </tr>
        </table>
      graph:
        x:
        - 36.98203228682706
        - 26.298015890356815
        - 37.87908932520544
        - 36.13905440483699
        - 51.59689204457815
        - 32.699423116289815
        - 29.505764785157417
        - 43.80191454962056
        - 15.923832525128997
        - 30.38969261144075
        - 33.22917312920818
        - 49.663066806145096
        - 33.028772893482035
        - 29.936415301181867
        - 40.16912714462593
        - 30.516702260052327
        - 26.59387488361448
        - 29.988256178908312
        - 32.90579455712431
        - 32.21354595040691
        y:
        - 20.526014504350073
        - 13.303868561609434
        - 20.042433664264795
        - 22.07859729125891
        - 26.61916621462425
        - 20.260122702181537
        - 18.78037274331512
        - 22.642613117645805
        - 11.462913609016901
        - 18.361476074298146
        - 19.702987197873476
        - 27.485717599037155
        - 19.15834784818139
        - 18.79626043659617
        - 21.394033971682493
        - 19.378869185051062
        - 19.832839118517082
        - 16.445275614221803
        - 20.158842127849745
        - 19.27833092813976
      part5:
        num1: 18
        num2: 25
        num3: 28
        num4: 6
        num5: 42
        num6: 11
        num7: 18
        num8: 6
        num9: 4
        num10: 18
        num11: 27
        num12: 3
        num13: 18
        num14: 24
        num15: 25
        num16: 27
        num17: 21
        num18: 36
        num19: 6
        num20: 24
        num21: 27
      description:
        num1: 18
        num2: 5.696
        num3: 1.404
        num4: 4.058
        num5: 0.001
        num6: 0.415
        num7: 0.04
        num8: 10.303
        num9: 0.0
        num10: 1.42
        num11: 85.5
        num12: 84.7
      part2:
        ans1:
          value: The value is meaningless
          feedback: Correct! Nice work
        ans2:
          value: The expected murder rate in metropolitan areas with no poverty is
            5.696.
          feedback: Correct! Nice work
        ans3:
          value: The expected murder rate in metropolitan areas with no poverty is
            0.415.
          feedback: Not quite - think about what the value represents.
        ans4:
          value: The expected murder rate in metropolitan areas with no poverty is
            -5.696.
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
          value: Poverty level explains $85.5\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Correct! Nice work
        ans2:
          value: Poverty level explains $92.47\%$ of the variability in murder rates
            in metropolitan areas.
          feedback: Not Quite. Please Try Again!
        ans3:
          value: Poverty level explains $84.7\%$ of the variability in murder rates
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