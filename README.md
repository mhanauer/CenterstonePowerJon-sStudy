---
title: "Centerstone Power Jon's Study"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
Need to think about Poission mediation regression.  Think about what each of these parameters would be.
```{r}
library(powerMediation)
ssMediation.VSMc.poisson(power = .8, 
                         b2 = .4, 
                         sigma.m = .4, 
                         EY = .4, 
                         corr.xm = .4, 
                         n.lower = 1, 
                         n.upper = 1e+30, 
                         alpha = 0.05, 
                         verbose = TRUE)
```





