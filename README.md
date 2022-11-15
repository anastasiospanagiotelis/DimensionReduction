# Dimension Reduction

These are notes and material from a course on Dimension Reduction originally given as part of the Australian Mathematical Sciences Institute (AMSI) Winter School. 

## Lectures

This short course covers:

1. Motivation
2. Principal Components Analysis (PCA)
3. Multidimensional Scaling (MDS)
4. Kernel PCA
5. Autoencoders
6. Manifolds
7. Isomap
8. Local Linear Embedding
9. Laplacian Eigenmaps 
10. Evaluation of Dimension Reduction techniques

All slides were made using Yihui Xie's [Xaringan](https://github.com/yihui/xaringan) package.  They are available on my [personal website](https://anastasiospanagiotelis.netlify.app/teaching/dimred/). They can be printed as pdf files using a browser with Google Chrome generally working best. Note that many of the plots are interactive and will not render well when printed as pdf.

If you want to build the slides yourself, simply clone the repository. Note that you will have to run the command ```xaringan::summon_remark()``` once before knitting the r markdown document.

## Textbook

The notes are my own but much of the course is inspired by the excellent text 

- Izenman, A. J. (2008). ["Modern multivariate statistical techniques. Regression, classification and manifold learning."](https://www.springer.com/gp/book/9780387781884), Springer. 

In particular Chapter 7 (especially section 7.2), Chapter 13 and Chapter 16 provide a good supplement to this course.

## Software

All coding is done using [R](https://www.r-project.org/) and the packages of the [tidyverse](https://www.tidyverse.org/). Of tremendous use is the package dimRed by Guido Kraemer available on [CRAN](https://cran.r-project.org/web/packages/dimRed/index.html) and [Github](https://github.com/gdkrmr/dimRed). The packages *broom*, *png* and *kpca* should also be installed if you want to work through the tutorials.

## Tutorials

Tutorials are available on the [course website](https://anastasiospanagiotelis.netlify.app/teaching/dimred/). A single R markdown file generates a pdf both with and without solutions. Simply change line 17 to *Tutorial 1 Solutions* or *Tutorial 2 Solutions* if you need to generate the files with solutions, and anything else if you do not want solutions.

## Data

Data can be found in the *data* folder. They are also available on the [course website](https://anastasiospanagiotelis.netlify.app/teaching/dimred/).  The datasets are:

- World Bank data on socioeconomic indicators (sourced from the [World Bank](https://data.worldbank.org/indicator))
- Data from an Irish Smart meter trial (collected by Council for Energy Regulation, see Council for Energy Regulation, (2011), "Electricity smart metering customer behaviour trials", **Tech. Report**)
- Data on images and the data on the word mother in different languages were constructed by me.
