# jiahao-mda
Mini Data Analysis for UBC STAT 545

## Overview
This repository contains milestones of a mini data analysis project on `cancer_sample` dataset. Files of milestone x is stored in directory `mx`, with the following listed files:
- `.rmd`: source code of R script and document
- `.md`: derived markdown file that is readable on github webpage
- `mx_files`: derived `.png` files which are graphs made from the R script

Parallel to the `mx` folders, there is an `output` folder that contains the output files derived from milestone 3:
- `cancer_sample_radius.csv`: csv file derived from tibble using I/O
- `model.rds`: model file derived from tiible

## Milestone 1
This milestone compares the given 8 datasets and finally selected `cancer_sample` for further study. It also contains several simple analysis with graphs as well as some potential research directions in the future. Report of this milestone is [here](m1/m1.md).

## Milestone 2
This milestone explores `cancer_sample` based on the 4 research questions proposed from [milestone 1](m1/m1.md). In the end, it refines the research questions from 4 to 2, and also offers a new version of the orginal dataset for further use. Report of this milestone is [here](m2/m2.md).

## Milestone 3
This milestone focuses on the refined 2 research questions from [milestone 2](m2/m2.md). It manipulated the data with factors, fits a model object to the data, as well as file I/O in the end. The derived files are stored in the `output` folder. Report of this milestone is [here](m3/m3.md).
