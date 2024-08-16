---
title: Variance of a mean
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: true
outcomes:
- 3.1.1.14
- 3.1.1.15
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
- CY
assets: null
part1:
  type: symbolic-input
  pl-customizations:
    label: $\sigma^2 = $
    variables: mu, sg, n
    weight: 1
    allow-blank: false
myst:
  substitutions:
    params:
      vars:
        title: Variance of a mean
      description:
        text: Suppose we have $n$ independent observations $X_1$, $X_2$, ..., $X_n$
          from a distribution with mean $\mu$ and standard deviation $\sigma$.
      part1:
        question: 'What is the variance of the mean of these $n$ values: $\frac{X_1
          + X_2 + \dots + X_n}{n}$?'
---
# {{ params.vars.title }}
{{ params.description.text }}

| For  | Use   |
|----------|-------|
| $\mu$  | mu  |
| $\sigma$  | sg  |
| $n$  | n  |
| $X_i$  | xi  |

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)