# Model and Cost function

## 1. Model Representation

* input variables, input features

$$ x^{(i)}$$

* output, target variable -> trying to predict element

$$y^{(i)}$$

* training example 

$$(x^{(i)}, y^{(i)})$$

* The data set
* m training example
* a training set

$$(x^{(i)}, y^{(i)})$$
$$i = 1,...,m$$

[img1](./img/img1.png)

* The goal is, given a training set, to learn a function h: X->Y so that h(x) is a excellent predictor for the corresponding value of y 


* When target variable is continuous, the learning problem is called a regression

* When target variable is discrete, the learning problem is called a classification

### Linear regression

* This is meaning to predict y that is linear func of x
* linear regression value is one that is x can predict all of prices

## 2. Cost Function

* Squared error function, Mean squared error
* measure the accuracy of hypothesis function 
* can know most closely function to data 
* takes an average difference of all the results of the hypothesis with inputs from x's and the actual output y's


[img2](./img/img2.png)

~~~
h_theta(x) = theta_0 + theta_1x
~~~

* theta_0 and theta are Parameters
* Measure theta by using cost function
* The smaller theta, the highr the accuracy
* The Cost functions is criteria for judgement to measure theta


