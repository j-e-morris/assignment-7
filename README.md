# Assignment 7 - Exploring R packages

### patchwork: the composer of ggplots

`patchwork` makes it simple to create complex (*& beautiful!*) plot layouts suitable for publication-worthy figures. Along with an extensive suite of helpful vignettes, `patchwork` has a very intuitive and readable coding syntax that makes it extremely easy to use. For example, to arrange two plots (`p1` & `p2`) side by side, you would 'add' the plots together using `p1 + p2`. Want them stacked vertically? Just 'divide' the plots using `p1 / p2`. Want a third plot (`p3`) to the right? 'Add' it to the nested plots using `(p1 / p2) + p3`. The possibilities are virtually endless.

There are a lot of things I love about `patchwork`: 
- The package automatically aligns plot dimensions, eliminating the need to painstakingly define plot coordinates. 
- The plot layout options are very versatile, allowing you to easily control plot arrangement, size, orientation, and add blank space. 
- The package allows for adding additional ggplot arguments (e.g., to unify themes across all plots), and annotations, including auto-tagging capabilities for identifying subplots in text. 
- `patchwork` can integrate components from other plotting packages like `cowplot` and `gridExtra`. 

The main drawback to `patchwork` is that all plots must be ggplot objects. Regardless, I would absolutely recommend this package to anyone looking for a simple but powerful way to combine multiple plots into a single multipaneled figure.


### Location
Download from [**CRAN**](https://cloud.r-project.org/web/packages/patchwork/index.html) 
``` {r}
install.packages('patchwork')
```
Development version from [**GitHub**](https://github.com/thomasp85/patchwork)
```{r}
# install.packages("devtools")
devtools::install_github("thomasp85/patchwork")
```


### Vignettes

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


### Applications
[Website](https://patchwork.data-imaginist.com/index.html):
Provides instructions for download and installation, vignettes, and helpful references.
