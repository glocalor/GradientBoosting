# GradientBoosting
GradientBoosting原理学习并用于解决Kaggle入门题目：
## Spaceship Titanic

Predict which passengers are transported to an alternate dimension

<b> 梯度提升算法(GradientBoosting)的核心是通过增加弱决策树，对损失函数的梯度进行更新，从而实现最小化损失函数</b>

GradientBoosting算法既可以用于回归问题，也可以用于解决分类问题

回归使用的损失函数是<b>MSE</b>，分类使用的是<b>对数似然</b>。

### 回归问题

既然是用梯度来最小化损失函数，我们有必要先引入损失函数

$$L=\frac1n\sum_{i=0}^n(y_i-\gamma)^2$$

$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$$









