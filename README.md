# Shiny App Tutorial for the *WRS2* Package

Code underlying the Shiny App found at https://ld19rk.shinyapps.io/WRS2/.

## Table of Contents
- [About](#about)
- [Installation](#installation)
- [Notes](#notes)

## About
For the second study of my dissertation, I was interested in the relationship between psychopathy and success in the Prisoner's Dilemma Game (PDG) under various conditions. In the first study of my dissertation, I conducted a meta-analysis examining (among other things) the nascent literature on this topic. Based on these empirical findings and theory, I identified three potentially relevant moderators: opponent strategy, match length, and *k*-index of the PDG. To examine the effect of these moderators, I identified several proxy strategies for psychopathy (i.e., Defector, AntiTitForTat, and TrickyCooperator) and simulated 200 matches for each interacting condition. Stochastic noise was added to the model to increase the generalizability of the simulation to experimental research. Further details can be gleaned from the Python script. 

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
