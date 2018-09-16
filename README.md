[![Build Status](https://travis-ci.org/liao961120/ling-rmd.svg?branch=master)](https://travis-ci.org/liao961120/ling-rmd)

# R Markdown as an Authoring Tool in Linguistics

This is the source of [R Markdown as an Authoring Tool in Linguistics](https://liao961120.github.io/ling-rmd).

## Reproduce

HTML format:

```r
rmarkdown::render("main.Rmd", output_format = "bookdown::html_document2")
```

PDF format:

```r
rmarkdown::render("main.Rmd", output_format = "bookdown::pdf_document2")
```
