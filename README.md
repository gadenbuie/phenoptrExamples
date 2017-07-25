# phenoptrExamples - Example data for use with the `phenoptr` package

<style type="text/css">
img { 
  border: none;
}
table {
    width: auto !important;
}
</style>

`phenoptrExamples` contains data sets and example code which demonstrate
the use of the `phenoptr` package.
`phenoptr` contains functions that make it easier to read and analyze data tables
and images created by PerkinElmer's inForm<sup>&reg;</sup> software.

`phenoptr` and `phenoptrExamples` are part of the PerkinElmer Phenoptics&trade;
family of
Quantitative Pathology Research Solutions. For more information
visit the Phenoptics&trade;
[home page](http://www.perkinelmer.com/cancer|immunology/index.html).

## Installation

Installation is from GitHub:

```
# install.packages("devtools")
devtools::install_github("PerkinElmer/phenoptrExamples", build_vignettes=TRUE)
```

### Package data

`phenoptrExamples` contains selected inForm output from nine images taken
from three samples of lung cancer tissue.

The tissue was stained with DAPI counterstain and Opal™ stains
and imaged on a 
Vectra® Polaris™ Automated Quantitative Pathology Imaging System.
The MSI images were unmixed to components, segmented and classified
with inForm® image analysis software. The files in the `extdata/samples`
directory are a selection of the inForm output from these images.

This table shows the Opal stains used, the epitope they were bound to,
and the colors used to show the stain in the composite and phenotype views.

Stain   | Epitope | Composite | Phenotype
--------|---------|-----------|----------
DAPI    | Nucleus | Blue      | N/A
Opal520 | PDL1    | Red       | N/A
Opal540 | CD8     | Yellow    | Yellow
Opal570 | FoxP3   | Orange    | Orange
Opal620 | CD68    | Magenta   | Magenta
Opal650 | PD1     | Green     | N/A
Opal690 | CK      | Cyan      | Cyan

### Full documentation

See the
[Articles](https://perkinelmer.github.io/phenoptrExamples/articles/index.html)
and
[Reference](https://perkinelmer.github.io/phenoptrExamples/reference/index.html)
sections of the full documentation for details.
