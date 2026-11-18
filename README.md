# Permutation T-Test Using Python

## 1. Introduction

A Permutation T-Test is a statistical method used to determine whether there is a significant difference between the means of two groups.

Unlike traditional statistical tests, the permutation test does not depend heavily on assumptions about the data distribution. It works by randomly rearranging the observations between groups and calculating the difference in means repeatedly.

This project demonstrates the working of a Permutation T-Test using Python.

## 2. Objectives

- To understand the concept of the Permutation T-Test.
- To compare the means of two different datasets.
- To generate random samples using Python.
- To understand the null hypothesis.
- To calculate statistical significance using permutation methods.
- To visualize the results using graphs.

## 3. Libraries Used

The project uses the following Python libraries:

- **NumPy:** Used for numerical calculations, generating random data and performing permutations.
- **Matplotlib:** Used for creating histograms and visualizing data.
- **SciPy:** Used for statistical calculations and probability analysis.

## 4. Data Generation

Two different datasets, Dataset A and Dataset B, are generated using Python.

Each dataset contains 100 observations.

The datasets are created using random numbers and mathematical transformations. Their distributions and mean values are compared to understand the differences between the two groups.

## 5. Permutation Test Procedure

The permutation test follows these steps:

1. Generate two sample datasets.
2. Combine both datasets into a single dataset.
3. Assign group labels to the observations.
4. Randomly shuffle the group labels.
5. Calculate the difference between the group means.
6. Repeat the random permutation process 1,000 times.
7. Create a distribution of mean differences under the null hypothesis.
8. Compare the observed difference with the permutation distribution.

## 6. Statistical Significance

Statistical significance helps determine whether the observed difference between two groups is meaningful.

The project calculates statistical significance using two methods:

- Z-value method.
- Permutation-based p-value method.

The p-value is used to evaluate the evidence against the null hypothesis.

A smaller p-value indicates stronger evidence that the observed difference is statistically significant.

## 7. Visualization

A histogram is created using Matplotlib to display the distribution of mean differences obtained from 1,000 permutations.

The observed difference between the original datasets is also displayed on the histogram.

This visualization helps understand whether the observed difference is unusual compared with the differences generated under the null hypothesis.

## 8. Result

The Python program successfully generates two datasets and performs a permutation test by randomly shuffling group labels.

The experiment produces a distribution of mean differences and calculates statistical significance using the generated permutation values.

The results demonstrate how permutation testing can be used to compare two groups.

## 9. Repository Link

GitHub Repository:

https://github.com/pappathipappathi026-cmyk/stats_ttest_permutation-1-/blob/main/24_stats_ttest_permutation%20(1).ipynb

## 10. Conclusion

The Permutation T-Test provides a useful method for comparing the means of two groups using random rearrangements of data.

This project demonstrates how Python libraries such as NumPy, Matplotlib and SciPy can be used to perform statistical analysis and visualize results.

Through this project, we understand the importance of hypothesis testing, random permutation, p-values and statistical significance in data analysis.
