# Shiny App Tutorial for the *WRS2* Package

Code underlying the Shiny App found at https://ld19rk.shinyapps.io/WRS2/.

## Table of Contents
- [About](#about)
- [Installation](#installation)
- [Notes](#notes)

## About

In my first year of my Ph.D., I completed the course PSYC 7V08: Using *R* for Reproducible Research (Brock University). The culminating project required students to create a tutorial for a package of their choice and deliver a presentation on this package to the class. I chose to create a Shiny App (https://ld19rk.shinyapps.io/WRS2/) that provides a tutorial on the *WRS2* package. This package centres around robust statistics, which enable the user to circumvent common obstacles in statistical analysis (e.g., outliers, skewed distributions) and estimate more accurate parameters than traditional methods. Example functions include robust alternatives to common statistical tests (e.g., independent samples *t*-tests). 

The tutorial provides the reader with the following:

* a brief walkthrough of general principles in robust statistics,
* examples of common functions on simulated data,
* interactive coding exercises,
* a multiple-choice pop-quiz,
* resources for further reading/viewing.

This repository contains the Markdown file with the code underlying the Shiny App tutorial.

## Installation

To run the Markdown script underlying the Shiny App tutorial, you must have *R* installed as well as the following packages:

* *learnr*
* *tidyverse*
* *tibble*
* *knitr*
* *jtools*
* *gt*
* *sn*
* *stfspack*
* *WRS2*
* *effectsize*
* *report*

## Notes

Shiny App was originally deployed in 2020 and redeployed in 2024 with no changes.
