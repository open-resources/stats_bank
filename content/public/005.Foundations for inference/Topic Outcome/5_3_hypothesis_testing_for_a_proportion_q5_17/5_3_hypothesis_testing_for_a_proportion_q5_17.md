---
title: Online communication
topic: Foundations for inference
author: Camilla Ren
source: OpenIntro Statistics Fourth Edition
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 5.1.1.23
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
- CR
assets: null
part1:
  type: checkbox
  pl-customizations:
    weight: 1
    partial-credit: true
myst:
  substitutions:
    params:
      vars:
        title: Online communication
      description:
        sample_size: 175
        num2: 0.56
        num3: 0.63
        num4: 56
        num5: 63
      part1:
        ans1:
          value: $H_0$ should be $p = 0.56$ (Null hypothesis should state that the
            population proportion is equal to 0.56.)
          feedback: Correct! (1) The hypotheses should be about the population proportion
            ($p$), not the sample proportion. (2) The null hypothesis should have
            an equal sign. (3) The alternative hypothesis should have a not-equals
            sign, and, (4) It should reference the null value, $p_0$ = 0.56, not the
            observed sample proportion.
        ans2:
          value: ' $H_0: p < 0.63$, $H_A: p > 0.56$ (Your friend''s proposed hypotheses
            are incorrect as indicated in the solution.)'
          feedback: ' Try Again! (1) The hypotheses should be about the population
            proportion ($p$), not the sample proportion. (2) The null hypothesis should
            have an equal sign. (3) The alternative hypothesis should have a not-equals
            sign, and, (4) It should reference the null value, $p_0$ = 0.56, not the
            observed sample proportion.'
---
# {{ params.vars.title }}
A study suggests that ${{ params.description.num4 }}$% of college student spend 10 or more hours per week communicating with others online.

You believe that this is incorrect and decide to collect your own sample for a hypothesis test.

You randomly sample ${{ params.description.sample_size }}$ students from your dorm and find that ${{ params.description.num5 }}$% spent 10 or more hours a week communicating with others online. A friend of yours, who offers to help you with the hypothesis test, comes up with the following set of hypotheses.

$$
\begin{align\*}
H_0&: p \< {{ params.description.num2 }} \\
H_A&: p > {{ params.description.num3 }}
\end{align\*}
$$

## Part 1

Identify any errors you see and choose the appropriate answer in the following.

### Answer Section

- {{ params.part1.ans1.value}}
- {{ params.part1.ans2.value}}
- {{ params.part1.ans3.value}}
- {{ params.part1.ans4.value}}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)