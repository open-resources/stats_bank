---
title: The Coast Starlight, Part I
topic: Introduction to linear regression
author: Paula Wong-Chung
source: original
template_version: 1.4
attribution: openintro-stats
partialCredit: true
singleVariant: false
showCorrectAnswer: false
outcomes:
- 8.1.1.1
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
- PW
- longtext
- number-input
assets:
- coast_starlight.jpg
- sample.html
part1:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer1.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
part2:
  type: longtext
  gradingMethod: Manual
  pl-customizations:
    placeholder: Type your answer here...
    file-name: answer2.html
    quill-theme: snow
    directory: clientFilesQuestion
    source-file-name: sample.html
part3:
  type: number-input
  pl-customizations:
    comparison: decdig
    digits: 3
    weight: 1
    allow-blank: true
    label: $r= $
myst:
  substitutions:
    params_vars_title: The Coast Starlight, Part I
    params_part3_num1: 0.685
---
# {{ params_vars_title }}
The Coast Starlight Amtrak train runs from Seattle to Los Angeles. The scatterplot below displays the distance between each stop (in miles) and the amount of time it takes to travel from one stop to another (in minutes).

<img src="coast_starlight.jpg" alt="A scatterplot is shown with about 15 points. The horizontal axis represents 'Distance (miles)' with values ranging from just over 0 to about 350. The vertical axis represents 'Travel Time (in minutes)' and has values ranging from about 20 to 380. The point with the smallest distance -- about 10 miles -- shows a travel time of about 40 minutes. Next, there is a cluster of 6 points with distances between 40 and 60 miles and travel times ranging from about 20 to 60 minutes. The remainder of the points are scattered pretty broadly but may show a slightly upward trend. A few points that highlight the widely varying nature of the data are located at the following approximate locations: (190 miles, 60 minutes), (240 miles, 250 minutes), (250 miles, 380 minutes), and (350 miles, 200 minutes)." width=400>

## Part 1

Describe the relationship between distance and travel time.

### Answer Section

Answer in 2-3 sentences, try and use full sentences.

### pl-answer-panel

There is a somewhat weak, positive, possibly linear relationship
between the distance traveled and travel time. There is clustering
near the lower left corner that we should take special note of.

## Part 2

How would the relationship change if travel time was instead measured in hours, and distance was instead measured in kilometers?

### Answer Section

Answer in 2-3 sentences, try and use full sentences.

### pl-answer-panel

Changing the units will not change the form, direction or strength
of the relationship between the two variables. If longer distances
measured in miles are associated with longer travel time measured in
minutes, longer distances measured in kilometers will be associated
with longer travel time measured in hours.

## Part 3

Correlation between travel time (in miles) and distance (in minutes) is $r = {{ params_part3_num1 }}$. What is the correlation between travel time (in kilometers) and distance (in hours)?

### Answer Section

Please enter in a numeric value.

### pl-answer-panel

Changing units doesn't affect correlation: $r = {{ params_part3_num1 }}$.

## Attribution

Problem is from the [OpenIntro Statistics](https://openintro.org/book/os/) textbook, licensed under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).<br>![Image representing the Creative Commons 4.0 BY license.](https://raw.githubusercontent.com/firasm/bits/master/by.png)