---
title: Matrix Completion for Different Missing Data Patterns
summary: A study of three matrix imputation methods on different types of missing data patterns 
tags:
- Representation Learning
date: "2019-11-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Matrix with missing entries
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/nhuang37/Matrix-Completion-for-Different-Missing-Data-Patterns

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

## Overview
Matrix completion and imputation is a common problem and an important cornerstone in data science applications. We compare the performance of three matrix imputation methods (Soft-Impute, SoftImpute-concat, Multiple Imputation) on different types of missing data patterns using both synthetic and real datasets. Although no method is found to perform significantly better under all circumstances, SoftImpute-concat indeed outperforms original SoftImpute when missing is not at random (NMAR) on our data. Besides, SoftImpute-concat has more robust performance than SoftImpute when missing rate increases. However, no theoretical proof of SoftImpute-concat superior performance under NMAR setting is given so far. Therefore, we discuss possible reasons based on a toy example.

## Data
1. Simulated Data
2. The MovieLens small dataset includes 100,000 ratings (ranging from 0.5 to 5) of 9000 movies by 600 users
3. EMBARC study, an 8-week randomized placebo-controlled clinical trial of sertraline enrolled about 300 patients with Major Depressive Disorder

## Algorithm
1. SoftImpute
2. SoftImpute-Concat
3. Multiple Imputation
