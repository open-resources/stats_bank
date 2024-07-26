---
title: Roulette
topic: Probability
author: Christina Yang
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
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
assets:
- roulette_bw.jpg
part1:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $E = \$$
part2:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 4
    weight: 1
    allow-blank: false
    label: $SD = \$$
myst:
  substitutions:
    params_vars_title: Roulette
    params_description_num_slots: 38
    params_description_num_red: 17
    params_description_num_black: 18
    params_description_num_green: 3
    params_description_bet_amount: 2
    params_description_bet_color: black
---
# {{ params_vars_title }}
The game of Roulette involves spinning a wheel with a number of colored slots. A ball is then spun onto the wheel and will eventually land in a slot, where each slot has an equal chance of capturing the ball. A photograph of an example (de-coloured) roulette wheel is shown below:

<figure>
  <img src="roulette_bw.jpg" width=175>
  <figcaption>Photo by <a href="https://www.pexels.com/photo/close-up-of-ball-on-russian-roulette-6664248/">Anna Shvets from Pexels</a></figcaption>
</figure>

You are working on creating a more interesting roulette wheel and create one with ${{ params.description.num_slots }}$ slots: ${{ params.description.num_red }}$ red, ${{ params.description.num_black }}$ black, and ${{ params.description.num_green }}$.

Gamblers can place bets on red or black. If the ball lands on their color, they double their money. If it lands on any other color, they lose their money. Suppose you bet ${{ params.description.bet_amount}} on {{ params.description.bet_color }}.

## Part 1

What's the expected value of your winnings? Round to 4 decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Part 1: E = {{ params.part1.correct }}

## Part 2

What's the standard deviation of your winnings? Round to 4 decimal places.

### Answer Section

Please enter a numeric value in.

### pl-answer-panel

Part 2: SD = {{ params.part2.correct }}

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)