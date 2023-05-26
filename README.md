# My Reproducible Project

## Project organization

-   PG = project-generated
-   HW = human-writable
-   RO = read only

### Equation Example

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are $$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

## Usage

wwerwerw

## Installation

    install.packages("tidyverse")

<!-- -->

    .
    ├── .gitignore
    ├── CITATION.md
    ├── LICENSE.md
    ├── README.md
    ├── requirements.txt
    ├── bin                <- Compiled and external code, ignored by git (PG)
    │   └── external       <- Any external source code, ignored by git (RO)
    ├── config             <- Configuration files (HW)
    ├── data               <- All project data, ignored by git
    │   ├── processed      <- The final, canonical data sets for modeling. (PG)
    │   ├── raw            <- The original, immutable data dump. (RO)
    │   └── temp           <- Intermediate data that has been transformed. (PG)
    ├── docs               <- Documentation notebook for users (HW)
    │   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
    │   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
    ├── results
    │   ├── figures        <- Figures for the manuscript or reports (PG)
    │   └── output         <- Other output for the manuscript or reports (PG)
    └── src                <- Source code for this project (HW)

## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## Getting Started

This was the sesssionInfo() contents:

```
R version 4.2.2 (2022-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19045)

Matrix products: default

locale:
[1] LC_COLLATE=Dutch_Netherlands.utf8  LC_CTYPE=Dutch_Netherlands.utf8   
[3] LC_MONETARY=Dutch_Netherlands.utf8 LC_NUMERIC=C                      
[5] LC_TIME=Dutch_Netherlands.utf8    

attached base packages:
[1] stats     graphics  grDevices datasets  utils     methods   base     

other attached packages:
[1] renv_0.16.0

loaded via a namespace (and not attached):
[1] compiler_4.2.2 tools_4.2.2   
```

There is also a renv lock.file that you can use using:

```
renv::restore()
```
