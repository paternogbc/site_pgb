---
title: teste rmarkdown
author: admin
date: '2020-04-30'
slug: teste-rmarkdown
categories:
  - Demo
tags:
  - Demo
subtitle: ''
summary: ''
authors: []
lastmod: '2020-04-30T19:57:07-03:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: yes
projects: []
output:
  blogdown::html_page:
    toc: true
    number_sections: false
    toc_depth: 2
    code_folding: hide
---

# Introduction

Lorem Ipsum é simplesmente uma simulação de texto da indústria tipográfica e de impressos, e vem sendo utilizado desde o século XVI, quando um impressor desconhecido pegou uma bandeja de tipos e os embaralhou para fazer um livro de modelos de tipos. Lorem Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica, permanecendo essencialmente inalterado. Se popularizou na década de 60, quando a Letraset lançou decalques contendo passagens de Lorem Ipsum, e mais recentemente quando passou a ser integrado a softwares de editoração eletrônica como Aldus PageMaker.


```r
library(tidyverse)
```

```
## ── Attaching packages ────────────────────────────────────────────────────────── tidyverse 1.3.0 ──
```

```
## ✓ ggplot2 3.3.0     ✓ purrr   0.3.4
## ✓ tibble  3.0.1     ✓ dplyr   0.8.5
## ✓ tidyr   1.0.2     ✓ stringr 1.4.0
## ✓ readr   1.3.1     ✓ forcats 0.5.0
```

```
## ── Conflicts ───────────────────────────────────────────────────────────── tidyverse_conflicts() ──
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```

```r
g1 <- 
  ggplot(iris, aes(Sepal.Length, Sepal.Width)) +
  geom_point() +
  geom_smooth()
g1
```

```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

<img src="/post/2020-04-30-teste-rmarkdown/index_files/figure-html/unnamed-chunk-1-1.png" width="672" />

```r
ggsave(filename = "featured.jpg", plot = g1)
```

```
## Saving 7 x 5 in image
```

```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

## Methods

Lorem Ipsum é simplesmente uma simulação de texto da indústria tipográfica e de impressos, e vem sendo utilizado desde o século XVI, quando um impressor desconhecido pegou uma bandeja de tipos e os embaralhou para fazer um livro de modelos de tipos. Lorem Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica, permanecendo essencialmente inalterado. Se popularizou na década de 60, quando a Letraset lançou decalques contendo passagens de Lorem Ipsum, e mais recentemente quando passou a ser integrado a softwares de editoração eletrônica como Aldus PageMaker.


```r
library(tidyverse)

g2 <- 
  ggplot(iris, aes(Petal.Length, Sepal.Width)) +
  geom_point() +
  geom_smooth()
g2
```

```
## `geom_smooth()` using method = 'loess' and formula 'y ~ x'
```

<img src="/post/2020-04-30-teste-rmarkdown/index_files/figure-html/unnamed-chunk-2-1.png" width="672" />



