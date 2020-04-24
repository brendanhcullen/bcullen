---
title: Predicting diabetes status from personality
summary: A machine learning project
abstract: ""
date: "2020-04-24T00:00:00Z"
image:
  caption: 
  focal_point: Smart
links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/brendanhcullen/personality-diabetes
- icon: link
  icon_pack: fas
  name: Pre-registration
  url: https://osf.io/nqs8e/

tags:
- machine learning
- health
- R
---

Prior research suggests that diabetes is both a cause and consequence of various health behaviors and thus has complex links to personality. This study investigates the utility of personality in predicting diabetes status (Type 1, Type 2 or none) using a subset of items from the Synthetic Aperture Personality Assessment (SAPA) Project (N ≈ 645,000). We estimate the classification accuracy of various personality measures, including low- and high-dimensional data, using supervised machine learning techniques, e.g. random forests, support vector machines and neural networks. Results are compared across machine learning models and dimensionality of personality predictors. This project involves the automated generation of executable R scripts using non-standard evaluation within a tidyverse framework, allowing for parallel processing on high-performance computing clusters. This analysis informs the extent to which personality measurement could be applied in clinical contexts related to diabetes.