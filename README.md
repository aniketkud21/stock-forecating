# Stock-Forecating

AIML Capstone Project - Stock Price Visualisation & Forecasting using Support Vector Regression

###Jay Jani - 2020300023
###Shubhan Kadam - 2020300026
###Aniket Kudtarkar - 2020300033

-------------------
PROBLEM STATEMENT
-------------------

Stock investments provide one of the highest returns in the market. Even though they are volatile in nature, one can visualize share prices and other statistical factors which helps the keen investors carefully decide on which company they want to spend their earnings on. 

Developing this simple project idea using the Dash library (of Python), we can make dynamic plots of the financial data of a specific company by using the tabular data provided by yfinance python library. On top of it, we can use a machine learning algorithm to predict the upcoming stock prices.

-------------------
ML ALGORITHM
-------------------

> Support Vector Machine
In machine learning, Support Vector Machines are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis. In Support Vector Regression, the straight line that is required to fit the data is referred to as hyperplane.

The objective of a support vector machine algorithm is to find a hyperplane in an n-dimensional space that distinctly classifies the data points. The data points on either side of the hyperplane that are closest to the hyperplane are called Support Vectors. These influence the position and orientation of the hyperplane and thus help build the SVM.

> Hyperparameters in SVR
Now that we have an intuition of what a support vector machine is, we will take look into the various hyperparameters that are used in Support Vector Regression. Some of the key parameters used are as mentioned below:

1. Hyperplane:
Hyperplanes are decision boundaries that is used to predict the continuous output. The data points on either side of the hyperplane that are closest to the hyperplane are called Support Vectors. These are used to plot the required line that shows the predicted output of the algorithm.

2. Kernel:
A kernel is a set of mathematical functions that takes data as input and transform it into the required form. These are generally used for finding a hyperplane in the higher dimensional space.

3. Boundary Lines:
These are the two lines that are drawn around the hyperplane at a distance of ε (epsilon). It is used to create a margin between the data points.

Support Vector Regression is a supervised learning algorithm that is used to predict discrete values. Support Vector Regression uses the same principle as the SVMs. The basic idea behind SVR is to find the best fit line. In SVR, the best fit line is the hyperplane that has the maximum number of points.

-------------------
Github Repository - https://github.com/aniketkud21/stock-forecating
-------------------






