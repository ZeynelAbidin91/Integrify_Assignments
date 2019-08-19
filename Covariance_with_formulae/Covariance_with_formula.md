
## Covariance Matrix with Formula

#### How to compute covariance matrix:

Variance is a measure of the variability or spread in a set of data. Mathematically, it is the average squared deviation from the mean score. We use the following formula to compute variance.

Covariance matrix is a matrix whose element in the i, j position is the covariance between the i-th and j-th elements of a random vector.

Basically the covariance matrix displays each covariance between each 2 features. 


```python
from IPython.display import Image
Image("covariance_formula.png")
```




![png](output_5_0.png)



Each row contains covariances of row's variable with the other variables. For example in the first row we can see each covariances between first variable and the others.

#### Using n-1 instead of n in calculating variance, covariance

The method is the use of n − 1 instead of n in the formula for the sample variance and sample standard deviation, where n is the number of observations in a sample. This method corrects the bias in the estimation of the population variance. It also partially corrects the bias in the estimation of the population standard deviation. However, the correction often increases the mean squared error in these estimations.
