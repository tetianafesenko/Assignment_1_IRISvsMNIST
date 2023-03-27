# Assignment_1_IRISvsMNIST

# Section 2: k-NN in Python [25 pts]
We have provided an example Google Colab notebook to describe how to implement k-NN using the
sci-kit learn library. 

This example uses MNIST, a popular toy dataset commonly used in ML that includes
images of hand-written digits. Sci-kit learn has multiple available toy datasets which you can see with this
link. 

Please look through the provided code carefully as hints have been placed to make this exercise
simpler!
#### 4. [15 pts] 

Using the provided notebook re-implement this algorithm using the Iris dataset (more details in Colab notebook).

HINT: The Iris dataset is not a dataset of images and is instead tabular data with 4 features (the petal length, the sepal length, the petal width, the sepal width). This will require you to comment out any sections of code that involve images (to comment out a line in Python, start that line with the # character).

###### a. Provide your Jupyter notebook so we can see your implementation [6 pts]
###### b. What was the optimal value of k for the Iris dataset and what was the test accuracy when it was evaluated? [5 pts]
###### c. How does the value of k compare to what we observed for MNIST? Why do you thinkthis is? [2pts]
###### d. When k becomes larger and close to the size of the training set the validation accuracy drops, why is that? [2pts]
#### 5. [10 pts] Using the same notebook you implemented for the IRIS dataset we would like to understand what happens when we work with lower dimensionality data. To simulate this only use the first two columns/features (sepal length and width) and re-run your model

HINT: This will involve changing your dataset immediately after using the sklearn load function.

###### a. What is the shape of the input data when you use only the first two features? [2 pt]
###### b. What was the optimal value of K for the Iris dataset and what was the test accuracy when it was evaluated? [5 pts]
###### c. How did this compare to when we previously used all of the data? [3 pts]

# Caregivers & Machine Learning Program 2023 - Vector Institute

BONUS Section 3: Math Questions [+10 pts]:

#### 6. [10pts] First, consider two independent univariate random variables X and Y sampled uniformly from the unit interval [0,1]. Determine the expectation E[Z] and variance Var[Z] of the random variable Z, defined as the squared distance 𝑍 = (𝑋 − 𝑌) 

You are allowed to evaluate integrals numerically (e.g. using scipy.integrate.quad or
scipy.integrate.dblquad), but you should explain what integral(s) you are evaluating,
and why.

