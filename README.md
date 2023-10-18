These materials are a computationally reproducible version of the paper:

Larkin, Oostenbroek, Lee, Hayward, Fernandez, Wang, Mitchell, Li & Meins (2023). A Smartphone App Effectively Facilitates Mothers’ Mind-Mindedness: A Randomized Controlled Trial, *Child Development*, in press.

The file manuscript.Rmd is an R markdown file that will perform all analyses and figure creation, and produce a pdf version of the manuscript.

The full repository can be downloaded (cloned), and contains all the required data files. 

The 'docker' directory contains a Dockerfile and instructions for making a local computationally reproducible version of the analysis. In addition, the Docker environment is set up to run automatically on a remote server via Github Actions, each time a change is made (i.e. on a 'commit' to the repo). The output document is then posted back to the main repository (manuscript.pdf). If you want to make changes to the analysis and have these build automatically, you can fork the repository into your own account.

Production of the reproducible version of this manuscript was supported by an Enhancing Research Culture award from [Research England](https://www.ukri.org/councils/research-england/).

![autobuild](https://github.com/bakerdh/testbabymind/workflows/autobuild/badge.svg)