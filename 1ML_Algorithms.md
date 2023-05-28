# ML Algorithms
Training set -> Learning Algorithm -> $f$  
Use the model $f$ to make the prediction $\widehat{y}$ or say the estimated target $y$ from through the feature $x$.  
Then, apply a cost function to evaluate the error between the prediction and the true ground.  
The goal is minimizing the cost function.
# **Models**
## Regression Models
Aim to predict numbers.
## 1. Linear Regression
**Univariate Linear Regression:** Basic form of linear regression with one variable/size/single feature: $f_{w,b}(x) = wx + b$.  
$w$ and $b$ here are called parameters.
## Classification Models
Aim to predict categories with small number of possible outputs.

# **Cost Function**
Aim to measure the error between the prediction $\widehat{y}$ and the true ground $y$. 
## 1. The Square Error Cost Function
$J(w,b) = \frac{1}{2m}\displaystyle\sum_{n=1}^m(\widehat{y}^{(i)}-y^{(i)})^2$.  
In the formula, there is $\widehat{y}^{(i)}=f_{w,b}(x^{(i)})$.  
Here, $m$ is the number of training examples.

