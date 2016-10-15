---
title       : Which feed produces the heaviest chickens?
subtitle    : A study of chicken feeds
author      : Daniel Jaeger
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz]  # {mathjax, quiz, bootstrap}
mode        : selfcontained

---
## Scope

In the associated Shiny tool, we study the effects of chicken feed on chicken weight.

We will use the R dataset chickwts, a very rich source of information!

---
## Data used
The chickwts dataset is from an experiment "to measure and compare the effectiveness of various feed supplements on the growth rate of chickens.  Per documentation in R: "Newly hatched chicks were randomly allocated into six groups, and each group was given a different feed supplement. Their weights in grams after six weeks are given along with feed types."

Below is a sample output from the dataset

```
##   weight      feed
## 1    179 horsebean
## 2    160 horsebean
## 3    136 horsebean
## 4    227 horsebean
## 5    217 horsebean
## 6    168 horsebean
```

---
## Findings

Sunflower and casein come in with the highest average chicken weight, above 300 grams.  The standard deviation for sunflower is slightly lower than casein.  Horsebean comes in at the lowest average chicken weight, 160 grams with tight standard deviation.

--- &radio
## Question

Now for a quiz question
Which feed produces the average heaviest chicken weight (using the mentioned dataset)?

1. meatmeal
2. horsebean
3. _sunflower_
4. soybean

*** .hint
Use the captioned Shiny tool to find the feed that has the highest everage Chicken Weight

*** .explanation
The average chicken weight for sunflower is 329 grams, the highest of the group.
