# An Ellipsoid Restrictive Region-based Regularization for Regression Analysis

_Abstract_

Machine Intelligence, as a domain, has evolved massively over the years and currently is a trending hot-cake, not only because of its ability to do a lot of tedious jobs efficiently but also because of its applicability in many disciplines of applied sciences. Regression is a statistical process in supervised machine learning that aims to develop a mathematical dependence between independent variables, such that the estimation error is minimized. One of the major challenges with Regression Analysis is Overfitting which results in almost negligible loss for each of the training data points, but the error explodes massively for testing data points. Several propositions are evident in the existing literature to address the Overfitting, like the Ridge ($\ell_2$ Norm) and Lasso ($\ell_1$ Norm) Regression. In this research a modified $\ell_{2}$ Norm based Regularization is proposed, with an ellipsoid restrictive region for the choice of parameters with the least residual error. The regression efficiency (to what extent, it counters Overfitting) for the modified $\ell_{2}$ Norm based Regularization is contrasted with that of $\ell_2$, and $\ell_1$ Norm based Regularization following its applicability on a few real-time datasets.



![https://github.com/Anurag-Dutta/ellipse_regg/blob/main/l_new.jpg](https://github.com/Anurag-Dutta/ellipse_regg/blob/main/l_new.jpg)

_Results_

a) Linear Regression

| Dataset                                      | Metrics | $\ell_1$ | $\ell_2$ | $\ell_\infty$ | $\ell_2$ (modified) |
|----------------------------------------------|---------|----------|----------|----------------|----------------------|
| California Housing Price                     | RMSE    | 0.7602   | 0.7308   | 0.7275         | **0.7264**           |
|                                              | MAE     | 0.6015   | 0.5644   | 0.5411         | **0.5468**           |
| Red Wine Quality                            | RMSE    | 0.8884   | 0.9015   | 0.8920         | **0.8823**           |
|                                              | MAE     | 0.7182   | 0.7319   | 0.7245         | **0.6958**           |
| White Wine Quality                          | RMSE    | **0.9004** | 0.9035   | 0.9044         | 0.9027               |
|                                              | MAE     | **0.7087** | 0.7094   | 0.7094         | 0.7103               |
| Burned Forest Area                          | RMSE    | 1.0069   | 1.0146   | 1.0069         | **1.0029**           |
|                                              | MAE     | 0.2794   | 0.3861   | 0.2376         | **0.3507**           |
| Concrete Compressive Strength               | RMSE    | 0.8750   | 0.8767   | 0.8713         | **0.8679**           |
|                                              | MAE     | 0.7116   | 0.7214   | 0.7096         | **0.7108**           |

b) Linear Regression

| Dataset                                      | Metrics | $\ell_1$ | $\ell_2$ | $\ell_\infty$ | $\ell_2$ (modified) |
|----------------------------------------------|---------|----------|----------|----------------|----------------------|
| California Housing Price                     | RMSE    | 0.7439   | 0.7448   | 0.7712         | **0.7240**           |
|                                              | MAE     | 0.5584   | 0.5568   | 0.5834         | **0.5486**           |
| Red Wine Quality                            | RMSE    | 0.9065   | 0.9084   | **0.8870**     | 0.8961               |
|                                              | MAE     | 0.7217   | 0.7263   | **0.6911**     | 0.7325               |
| White Wine Quality                          | RMSE    | 0.9526   | 0.9079   | 0.9177         | **0.9032**           |
|                                              | MAE     | 0.7165   | 0.7066   | 0.7262         | **0.7282**           |
| Burned Forest Area                          | RMSE    | 1.0101   | 1.0050   | 1.0067         | **1.0042**           |
|                                              | MAE     | 0.2969   | 0.2974   | 0.3293         | **0.3233**           |
| Concrete Compressive Strength               | RMSE    | 0.8836   | **0.8760** | 0.8826       | 0.8771               |
|                                              | MAE     | 0.7179   | **0.7133** | 0.7156       | 0.7150               |
