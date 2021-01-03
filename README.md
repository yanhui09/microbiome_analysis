# microbiome_analysis
Repository for the microbiome analysis

Steps to render the static website:
1. Render *.Rmd files  in R after install [rmarkdown](https://rmarkdown.rstudio.com/authoring_quick_tour.html).

```r
rmarkdown::render("1_microbiome_r.Rmd")
rmarkdown::render("index.Rmd")
```
2. build a static website with rendered *.html files, following the structure of _site.yml

```r
rmarkdown::render_site()
```

More details about R markdown can be found on Rstudio website: [here](https://rmarkdown.rstudio.com/authoring_quick_tour.html) and [there](https://rmarkdown.rstudio.com/lesson-1.html).