<h1 align = 'center'>Heart Disease Prediction Using Softmax Regression (from Scratch)</h1>

In this end-to-end Machine Learning project, I have created and trained a model from scratch, using NumPy, that uses the Multinomial Logistic (Softmax) Regression algorithm to predict the presence (and severity) of heart disease within a patient.

[Here is my blog post on Towards Data Science](https://towardsdatascience.com/ml-from-scratch-multinomial-logistic-regression-6dda9cbacf9d) regarding the same project where I've gone in detail over the project, explaining everything in a project-based tutorial format. Please do check out the blog for more info.

<h2>Understanding the Problem Statement</h2>

For this project, I have used the popular [UCI Cleveland Heart Disease](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) dataset for training the model and making predictions.

This is a multi-class classification based problem, where, on the basis of the available set of features (explained in the table given below), the model predicts one of the five possible outcomes (classes) for the patient's heart's condition-

* 0 : No heart disease; patient healthy
* 1-4 : Distinguished presence of heart disease
  * 1 : Minor heart ailment
  * 2 : Slightly severe heart ailment
  * 3 : Very serious ailment
  * 4 : Possibly fatal heart ailment
  
Given below is the list of features considered for training and making predictions. Note that most of these features can be obtained by simple blood tests, physical tests & ECG (Echo-Cardio-Gram) of the patient. A few require slightly more advanced imaging tests like fluoroscopy.
  
![](https://miro.medium.com/max/1400/1*A03KDT7F2GRpSQq4OHVd5Q.jpeg)

<h2>Key Project Takeaways</h2>

For this project, I got hands-on experience with the following machine learning techniques-
* Data wrangling for preprocessing and cleaning the training and testing data
* Building an efficient classification model from scratch using NumPy
* Mathematics behind softmax regression and SGD optimization

  
  
