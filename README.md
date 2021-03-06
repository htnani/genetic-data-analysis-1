# Analysis of Genetic Data 1: Inferring Population Structure

Materials for the RCC workshop, "Analysis of Genetic Data 1: Inferring
Population Structure".

**Date:** Tuesday, Feburary 13, 2018<br>
**Time:** 2:00 pm to 4:30 pm<br>
**Location:** Zar Room, John Crerar Library
([OpenStreetMap](https://www.openstreetmap.org/search?query=john%20crerar%20library#map=18/41.79053/-87.60282))<br>
**Instructor:** Peter Carbonetto

## Introduction

During this short workshop, we will apply simple numeric techniques to
investigate human genetic diversity and population structure from
large-scale genetic data sets. We will use popular software tools such
as PLINK and ADMIXTURE to prepare and analyze the "raw" genetic data,
and we will use R to visualize the results of our analyses. While
anyone who is curious about the "genomics revolution" may attend, this
workshop is mainly intended to develop practical computing skills for
graduate students and other researchers working with genetic
data-concepts such as "genotype" and "allele frequency" will not be
explained. We will practice "live coding" throughout, so please bring
your laptop!

## Prerequisites

This workshop assumes participants are already familiar with R and a
UNIX-like shell environment. An RCC user account is recommended, but
not required-temporary access to the RCC cluster will be available in
class. All participants must bring a laptop with a Mac, Linux, or
Windows operating system that they have administrative privileges on.

## Other information

+ This workshop attempts to apply elements of the
[Software Carpentry approach](http://software-carpentry.org/lessons).
See also
[this article](http://dx.doi.org/10.12688/f1000research.3-62.v2).
Please also take a look at the [Code of Conduct](conduct.md), and
the [license information](LICENSE.md).

+ To generate PDFs of the slides from the R Markdown source, run `make
slides.pdf` in the [docs](docs) directory. For this to work, you will
need to to install the
[rmarkdown](https://cran.r-project.org/package=rmarkdown) package in
R, as well as the packages used in [slides.Rmd](code/slides.Rmd). For
more details, see the [Makefile](docs/Makefile).

+ See also the [instructor notes](NOTES.md).

## Credits

These materials were developed by
[Peter Carbonetto](http://pcarbo.github.io) at the
[University of Chicago](https://www.uchicago.edu). Thank you to
[Matthew Stephens](http://stephenslab.uchicago.edu) for his support
and guidance. Also thanks to
[David Reich](http://reich.hms.harvard.edu) and his lab for making a
portion of the Affymetrix Human Origins data set available for public
use.
