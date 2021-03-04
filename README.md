# Assignment 7 - Exploring R packages

## `patchwork`


### LOCATION
Download from **CRAN**: https://cloud.r-project.org/web/packages/patchwork/index.html 
``` {r}
install.packages('patchwork')
```
Development version from **GitHub**: https://github.com/thomasp85/patchwork
```{r}
# install.packages("devtools")
devtools::install_github("thomasp85/patchwork")
```

### VIGNETTES

[Reference manual](https://cran.r-project.org/web/packages/patchwork/patchwork.pdf):
Describes package information and details main functions. 

[Getting Started](https://cloud.r-project.org/web/packages/patchwork/vignettes/patchwork.html):
Tutorial for working through the basics of using `patchwork`. Includes example plots, basic use, controlling layout, stacking and packing plots, and annotating the composition.

[Plot Assembly](https://patchwork.data-imaginist.com/articles/guides/assembly.html):
Tutorial of the different operators and functions available for plot assembly. Includes adding plots to the patchwork, nesting the left-hand side, and modifying patches.

[Controlling Layouts](https://patchwork.data-imaginist.com/articles/guides/layout.html):
Tutorial for controlling plot layouts. Includes adding an empty area, controlling the grid, moving beyond the grid, fixed aspect plots, insets, and controlling guides.

[Adding Annotation and Style](https://patchwork.data-imaginist.com/articles/guides/annotation.html):
Tutorial for adding titles, subtitles and captions, tagging, and styling the patchwork.

[Multipage Alignment](https://patchwork.data-imaginist.com/articles/guides/multipage.html):
Tutorial for aligning plots across pages, especially useful for designing slideshows.

### APPLICATIONS
[Website](https://patchwork.data-imaginist.com/index.html):
Download and installation instructions, vignettes, and helpful references.

### REVIEW
`patchwork` makes it simple to create complex plot layouts. 
