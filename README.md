# Class-imbalanced-learning
This file is used to record research work on class imbalanced problem


### resampling styles: (consideri each class's probability)
+ (original) uniform: $p_i = n_i / \sum_j(n_j)$
+ class-balanced: $p_i = 1/c$
+ reverse: $p_i = (1/n_i) / \sum_j (1/n_j)$



### reweighting styles: (consider each example's weight)
+ (original) uniform: $w_(x^i) = 1.0$  
+ repociral to example number of each class: $w(x^i) = \frac{1}{n_i}$)
+ effective number: 
+ repociral to $w(x^i) = \frac{1}{n_i^2}$)

The relationship is $p_i = w(x^i)\times n_i $
