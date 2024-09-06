### What is Machine Learning? 

> A computer program is said to learn from experience E with respect to some class of tasks T, and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E. 

##### Supervised Learning

> Common form of ML is supervised learning. The output, O, learns from inputs (x) and outputs (y) 
> 
> Inputs (x) are known as features, covariates or predictors.
> Outputs (y) are known as labels, targets, or responses.   
>
> Feeding the model with inputs and known outputs is the training set, which creates a performance P with the testing data. 

##### Exploratory Data Analysis 

> Obvious pattern recognition (exploratory data analysis)
> Common to make a pair plot where there are a small number of features 
> Also common to perform dimensionality reduction -> visualize data in 2d or 3d (identify patterns) 

##### Empirical Risk 

> Minimize the average loss (risk) over the training dataset. 

$$
\hat{\theta} = \arg\min_{\theta} \frac{1}{n} \sum_{i=1}^{n} \ell \left( y_i, f(x_n ; \theta \right))
 $$
Where: 
- **$\hat{\theta}$** is the parameter vector that minimizes the empirical risk.
- **$n$** is the number of training samples.
- **$\ell$** is the loss function.
- **$f_{\theta}(x_i)$** is the model's prediction for input $x_i$.
- **$y_i$** is the true value corresponding to input $x_i$.

Also where:

- **$\ell (e)$** is the binary indicator function, returns 1 if and only if the condition e is true, and returns 0 otherwise. (Binary returning a true or false integer or feature)

> Idea is the mninimize the function, or fitting/training the parameters that minimize the function above. 

### Softmax function    