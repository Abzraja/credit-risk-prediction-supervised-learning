# Credit Risk Prediction



### Summary
Exercise in using Supervised Learning to predict credit risk. 
* 2 sets of loans data used
* 2019 loans data used to train algorithm
* 2020 loans data used to test and make predictions on
* Data was cleaned and normalized where necessary
* Categorical data was converted to numerical data using Pandas dummies function.
* Data was split into train and test sets by dropping labels.
* Logistic Regression and Random Forest Classifier models trained and scored.

### Code and Analysis
The task was done in Jupyter Notebook and the file is contained in the Notebooks folder. Filename is Credit Risk Evaluator.ipynb


### Regression and Classification
Supervised learning problems can be either Regression problems or Classification problems.
I used both Logistic Regression and Random Forest Classifier models to evaluate and analyse the outcome of each.


### What is Logistic Regression
>Logistic regression, despite its name, is a classification model rather than regression model. Logistic regression is a simple and more efficient method for binary and linear classification problems. It is a classification model, which is very easy to realize and achieves very good performance with linearly separable classes. It is an extensively employed algorithm for classification in industry. The logistic regression model, like the Adaline and perceptron, is a statistical method for binary classification that can be generalized to multiclass classification. Scikit-learn has a highly optimized version of logistic regression implementation, which supports multiclass classification task.
<cite>https://www.sciencedirect.com/topics/computer-science/logistic-regression</cite>

Binary classification means the prediction is either true or false. Instead of fitting a linear line to the data like in Linear Regression, an S-shaped logistic function is fit to the data instead. The S-shaped curve goes from 0-1 and denotes the probability of the label being true of false based on the features.


### What is Random Forest
Random Forests are built from decision trees. Decision trees are easy to build and interpret but in practice are not accurate.

> Trees have one aspect that prevents them from being the ideal tool for predictive learning, namely inaccuracy.
<br/><cite>The Elements of Statistical Learning</cite>

Decision trees work well with the data used to create them, but are not flexible when classifying new samples.

Random Forests combine the simplicity of decision trees with flexibility, resulting in a vast improvement in accuracy.

<br />
<br />
<hr />
<br />

<img width="150" src="https://drive.google.com/uc?export=view&id=1OH_TvDjISYpoKL_98Jx3CDFPM7Xp8J6H">

### Abz Raja
abzraja@gmail.com
