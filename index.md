---
title       : slide
subtitle    : slidex
author      : me
job         : course taker
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap, interactive, shiny]
#      {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

Test slide 2

$x^2$
$$\frac{-b \pm \sqrt{b^2 - 4 a c}} {2a}$$



```
## [1] 55
```

```
## [1]  1  2  3  8  9 10
```

```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##    1.00    2.25    5.50    5.50    8.75   10.00
```

--- &radio
## Question 3

What is 1 + 1?

1. 1
2. _2_
3. 3
4. 10

*** .hint
It's between 1 and 3

*** .explanation
It's a matter of simple math

--- .class #id 

## Slide 4

Test slide 4

$x^3$
$$\frac{-b \pm \sqrt{b^2 - 4 a c}} {2a}$$

Must load knitr for R to work


```
## [1]  1  2  3  8  9 10 20 23
```

```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##    1.00    2.75    8.50    9.50   12.50   23.00
```






