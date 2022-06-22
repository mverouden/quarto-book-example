---
title: 'Quarto Book example'
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->



Quarto Book example source files to make a website, pdf and epub.

## Versions
Quarto: `sh quarto --version` results in 0.9.607

## Render README.Rmd
To make the README.md file, use:

```r
knitr::knit(input = "./README.Rmd")
```
