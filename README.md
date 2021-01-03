# microbiome_analysis
Repository for the Github pages: [Microbiome analysis at KU FOOD](https://yanhui09.github.io/microbiome_analysis/)

Steps to render the static website:
1. Render *.Rmd files  in R after install [rmarkdown](https://rmarkdown.rstudio.com/authoring_quick_tour.html).

```r
rmarkdown::render("1_microbiome_r.Rmd")
rmarkdown::render("index.Rmd")
```
2. Build a static website with rendered *.html files, following the structure of _site.yml

```r
rmarkdown::render_site()
```
3. change `_site/` according to your choice (/docs is used to hold Github pages)

```bash
mv _site docs
```
More details about R markdown can be found on Rstudio website: [here](https://rmarkdown.rstudio.com/authoring_quick_tour.html) and [there](https://rmarkdown.rstudio.com/lesson-1.html).
