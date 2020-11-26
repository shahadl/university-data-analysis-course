# Principal Components Analysis
A project within the university's "data analysis" course.

## Table of Contents
1. [Overview](#over)
3. [Description of the contents](#files)
4. [Results](#results)

## Overview <a name="over"></a>
What is Principal Components Analysis?

Principal Components Analysis is a statistical technique to extract patterns in a dataset, usually used as a dimensionality reduction method.
in my project i've calculated the PCA both manually and by R package called "prcomp", the goal of the project is to reduce the variables so that i can know an appropriate classfication that explains the different of the protein sources.

The second part is aboute performing leave one out cross validation "LOOCV" to oil data.

## Description of the contents <a name="files"></a>
- `PCA.ipynb` is a jupyter notebook contains a walkthrough of the project in R programming language.
- `protein.csv` the data i've used in the first part of the project, it is about the sources of the protein consumed in 25 European countries.
- `oil.csv` the data i've used in the first part of the project, it contains a percentages of different types of residuals during the analysis of crude oil obtained from 2 different fields

## Results <a name="results"></a>
### I tried to classify the European countries according to their wealth and poverty "rich\mid\poor".
![Outputt](https://github.com/shahadl/university-data-analysis-course/blob/main/Principal_Components_Analysis/image/output.png)

### This plot shows me that the first two components helped to separate the groups very well,

> ### it does make sense that `rich countries` tend to consume protein from sources that have high price like:white meat, red meat, milk and eggs.
> ### And the `middle income countries` tend to consume protein from sources that have low price like:cereal, nuts, fruits and vegetables.
