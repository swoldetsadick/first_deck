---
title       : Hello World
subtitle    : Here I am
author      : Bura Kereyou
job         : Doma Kofari
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
logo : logo.png
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- &radio 

## Slide 2

What is 1 + 1 ?

1. 1
2. _2_
3. 3
4. 4
*** .hint 
This is not a hint
*** .explanation 
This is a better explanation

---
## Slide 3

```r
sum(1:10)
```

```
## [1] 55
```

```r
10*(11)/2
```

```
## [1] 55
```
