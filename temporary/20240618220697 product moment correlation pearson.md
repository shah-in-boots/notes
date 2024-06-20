---
date: 2024-06-18
category: temporary
stage: considering
tags:
  - todo
---

The Pearson correlation coefficient is called a "product-moment correlation" because it is calculated using the product of the deviations of each pair of observations from their respective means (the "product") and then considering the average or expected value of these products (the "moment").

Here’s a detailed breakdown of the terms "product" and "moment":

### Product:

In the context of the Pearson correlation coefficient, the "product" refers to the multiplication of the deviations of each observation in the two variables from their respective means. Specifically, for each pair of observations (xi,yi)(x_i, y_i)(xi​,yi​):

(xi−xˉ)(yi−yˉ)(x_i - \bar{x})(y_i - \bar{y})(xi​−xˉ)(yi​−yˉ​)

These products capture how much each pair of observations deviates together from their means. A positive product indicates that both values are above or below their means, suggesting a positive relationship, while a negative product indicates that one value is above its mean and the other below, suggesting a negative relationship.

### Moment:

In statistics, a "moment" is a measure that provides information about the shape of the distribution of a set of values. The Pearson correlation coefficient uses the first moment about the mean, which is the average of the products of the deviations (also known as the covariance). By normalizing this covariance by the product of the standard deviations of the two variables, we get the Pearson correlation coefficient. This normalization scales the value to fall between -1 and 1, providing a standardized measure of linear association.

### Combining Product and Moment:

The Pearson correlation coefficient (rrr) can be written as:

r=∑i=1n(xi−xˉ)(yi−yˉ)∑i=1n(xi−xˉ)2∑i=1n(yi−yˉ)2r = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2 \sum_{i=1}^{n} (y_i - \bar{y})^2}}r=∑i=1n​(xi​−xˉ)2∑i=1n​(yi​−yˉ​)2​∑i=1n​(xi​−xˉ)(yi​−yˉ​)​

Here’s how it combines both concepts:

1. **Product of Deviations:** The numerator ∑i=1n(xi−xˉ)(yi−yˉ)\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})∑i=1n​(xi​−xˉ)(yi​−yˉ​) is the sum of the products of the deviations of each observation pair from their means, representing the co-movement of the variables.
2. **Moment (Covariance):** This sum of products can be seen as the covariance between XXX and YYY, which is a measure of how much the variables change together.
3. **Normalization:** The denominator ∑i=1n(xi−xˉ)2∑i=1n(yi−yˉ)2\sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2 \sum_{i=1}^{n} (y_i - \bar{y})^2}∑i=1n​(xi​−xˉ)2∑i=1n​(yi​−yˉ​)2​ normalizes the covariance by the product of the standard deviations of XXX and YYY, providing a dimensionless measure that lies between -1 and 1.

In summary, the Pearson correlation coefficient is called a "product-moment correlation" because it uses the product of the deviations of the observations from their means and considers the average (moment) of these products to measure the strength and direction of the linear relationship between two variables.