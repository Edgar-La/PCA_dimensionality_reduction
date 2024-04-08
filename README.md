# Principal Component Analysis: A dimensionlity reduction algorithm

## 1) Theory - _example on paper_
### Data
Given the 2d data:
|   |x  |y |
|---|---|---|
| 0 |3  |2  |
| 1 |4  |1  |
| 2 |0  |-3 |
| 3 |-1 |4  |
| 4 |-6 |1  |
| 5 |-5 |0  |
| 6 |3  |1  |
| 7 |1  |-4 |
| 8 |-4 |2  |
| 9 |1  |-1 |




### Standardize data

$x_{std} = \frac{x - \mu_x}{\sigma_x}$


|   |   x        |   y        |
|----|------------|------------|
| 0  | 0.962093   | 1.055396   |
| 1  | 1.245061   | 0.633238   |
| 2  | 0.113187   | -1.055396  |
| 3  | -0.169781  | -1.477555  |
| 4  | -1.584624  | 0.633238   |
| 5  | -1.301655  | 0.211079   |
| 6  | 0.962093   | 0.633238   |
| 7  | 0.396156   | -1.477555  |
| 8  | -1.018687  | 1.055396   |
| 9  | 0.396156   | -0.211079  |


### Calculate covariance matrix
### Build $\lambda$ identity matrix and sustract covariance matrix
### Calculate determinant of previous matrix
### Solve the equation for $\lambda$ value to find eigenvalues
### Find eigenvectors
### Dimensionality projections

## 2) Implementation - _PCA from scratch_

## 3) Comparison - _Implementation with Scikit Learn_

