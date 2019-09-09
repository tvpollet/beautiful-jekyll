---
layout: page
title: Meta-analysis course (in R)
subtitle:  a minore ad maius
published: true
---

## General info.

The course runs for the first time at an HBES funded workshop in Natal (Brazil) in Sept. 2019. I'll aim to make all my materials available via this website. The sources are listed at the end of each lecture as well as embedded. (Please also note the [disclaimer](/disclaimer) below and on each of the slides). 

This course relies heavily on various tutorials and books, in no particular order, by [Harrer on doing meta-analysis](https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/), the [book by Borenstein et al. (2009)](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470743386) the [R book by Schwarzer](https://www.springer.com/gp/book/9783319214153), [the book by Chen & Peace on applied meta-analysis in R](https://www.crcpress.com/Applied-Meta-Analysis-with-R/Chen-Peace/p/book/9781466505995), the [book by Mike Cheung on MetaSEM](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118957813), [the metafor package page](metafor-project.org/doku.php), [slides by B. Wiernik](https://wiernik.org/wp-content/uploads/2015/04/Wiernik-2015-Meta-analysis-Workshop.pdf), [the handbook of Meta-analysis in Ecology and Evolution by Koricheva and colleagues](https://press.princeton.edu/titles/10045.html), and the workshop materials of [Weiss & Daikeler (2017)](https://www.gesis.org/en/services/events/gesis-training/training-archiv/summer-school/2017/week-3/c9-meta-analysis-in-survey-methodology) shared by my colleague. Please see the citations in the course materials.

Please contact [me](mailto:t.v.pollet1981@gmail.com) should you spot any glaring errors, omissions or would like to suggest improvements.  

## Prerequisites.

Please have [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/) installed on your machine.

This short course is aimed at postgraduate level. You should have a basic understanding of statistical concepts, as covered at undergraduate level, such as for example: probability, a probability sample, statistical distributions, a _t_-test, correlation, OLS Regression.	

## Outcomes.

In this short course, I'll walk you through all the steps involved in carrying out a meta-analysis. 

By the end of this course, you should be able to understand published meta-analyses and conduct your own full-blown meta-analysis in R. We'll do our very best to give you the tools to become an expert, but I have no illusion(s) that you'll be an expert after just 6 short sessions. So, it's more of a 'crash course' - I recommend you read the cited sources and if in doubt ask the help of a statistician and/or consult [stats.stackexchange](https://stats.stackexchange.com/)

In more detail, in this course, we'll cover what a systematic review vs. a meta-analysis is. We'll then do some baby-steps in R. In the next session, I review common effect size families, such as Pearson _r_ or Cohen's _d_. In the third session, we'll discuss how we can synthesise those effect sizes and the differences between a fixed and random effect meta-analysis. Up until now, we have assumed that everything is hunky-dory, but one key issue which could affect _all_ meta-analyses is publication bias. In session 4, we define the problem and discuss some tests which have been suggested to allow us to detect potential publication bias (and their limitations). In session 5, we explore how we might make sense of observed heterogeneity via subgroup analysis and/or meta-regression. In the final session (session 6), we will cover advanced topics in meta-analysis, such as multilevel meta-analysis, a very basic structural equation modelling approach and (frequentist) network meta-analysis.

In the interest of time, there are some topics/issues which I will not cover (e.g., Bayesian meta-analyses, complex SEM, more advanced network meta-analyses, phylogenetic meta-analyses) but I can point you in the relevant directions should you need these.

## Sessions.

Note that you might require files to run .rmd, so please see the corresponding GitHub site.

Use the arrows to navigate the slides and press F for full screen in your browser. More shortcuts [here](https://github.com/hakimel/reveal.js/wiki/Keyboard-Shortcuts?)

1. [Session 1: Introduction to systematic reviews, meta-analysis and R](https://tvpollet.github.io/Meta-analysis_1/Meta-analysis_1.html#1) and [.rmd](https://github.com/tvpollet/Meta-analysis_1/blob/master/Meta-analysis_1.Rmd). Files can be found [here](https://github.com/tvpollet/Meta-analysis_1/)

2. [Session 2: All about effect sizes...](https://tvpollet.github.io/Meta-analysis_2/Meta-analysis_2.html#1) and zipped [.rmd](https://github.com/tvpollet/Meta-analysis_2/blob/master/Meta-analysis_2.rmd.zip). Files can be found [here](https://github.com/tvpollet/Meta-analysis_2/)

3. [Session 3: Fixed vs. random effects meta-analysis](https://tvpollet.github.io/Meta-analysis_3/Meta-analysis_3.html#1) and [.rmd](https://github.com/tvpollet/Meta-analysis_3/blob/master/Meta-analysis_3.Rmd). Files can be found [here](https://github.com/tvpollet/Meta-analysis_3/)

4. [Session 4: Publication bias](https://tvpollet.github.io/Meta-analysis_4/Meta-analysis_4.html#1) and [.rmd](https://github.com/tvpollet/Meta-analysis_4/blob/master/Meta-analysis_4.Rmd). Files can be found [here](https://github.com/tvpollet/Meta-analysis_4/)

5. [Session 5: Meta-regression and subgroup analyses](https://tvpollet.github.io/Meta-analysis_5/Meta-analysis_5.html#1) and [.rmd](https://github.com/tvpollet/Meta-analysis_5/blob/master/Meta-analysis_5.Rmd). Files can be found [here](https://github.com/tvpollet/Meta-analysis_5/)

6. [Session 6: Advanced topics: Multilevel, basic SEM, basics of network meta-analysis,... .](https://tvpollet.github.io/Meta-analysis_6/Meta-analysis_6.html#1) and [.rmd](https://github.com/tvpollet/Meta-analysis_6/blob/master/Meta-analysis_6.Rmd). Files can be found [here](https://github.com/tvpollet/Meta-analysis_6/)

Slides were made with the amazing [xaringan](https://github.com/yihui/xaringan) package in R.


## Exercises.

**To be added.** 

These are the solutions, no peeking (ahum).

1. [Exercise 1]() and [.rmd]()

2. [Exercise 2]() and [.rmd]()

3. [Exercise 3]() and [.rmd]()

4. [Exercise 4]() and [.rmd]()

5. [Exercise 5]() and [.rmd]()

6. [Exercise 6]() and [.rmd]()

## GoSoapbox.

For the interactive bits: [https://app.gosoapbox.com/](https://app.gosoapbox.com/) , the code is 257-883-396

## Youtube channel.
Occasional screencasts of my lectures can be found [here](https://www.youtube.com/channel/UCWXTuZsVGQzQTUJPkEjo0YQ/featured?view_as=subscriber).  I'll aim to make screencasts for recurrent questions by students.

## Statistical Glossary.

Struggling with some statistical terms? Have a look [here](https://tvpollet.github.io/PY_0782/glossary_stats.html)

## Acknowledgments.

Please see the end of each slides. My colleagues have provided generous input to these materials. My funding sources are listed in the slides. The workshop was generously financed by [HBES](www.hbes.com).

## Further reading.

**To be added.** 

See the slides.


##### [Disclaimer](https://tvpollet.github.io/disclaimer/)