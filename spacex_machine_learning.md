# SpaceX Machine Learning

This was part of the Applied Data Science Capstone final project included in the course in Coursera's IBM Data Science Professional Certificate program. Developed in Python. 

## Project Details
This project was a part of the 8-series sections of the Applied Data Science Capstone course by IBM.

The objectives of this project are to:

- Perform Exploratory Data Analysis and determine training labels
- Create a column for the class
- Standardize the data
- Split into training data and test data
- Find the best hyperparameter for Logistic Regression, SVM, Decision Tree Classifier, and KNN
- Find the method that performs best using test data

## Project Outcome

### Confusion Matrix
<img src="images/confusion_matrix.png?raw=true" width="600" height="500"/>

_Confusion matrix for the logistic regression model. Examining the confusion matrix, we see that logistic regression can distinguish between the different classes. We see that the major problem is false positives._ 

<img src="images/confusion_matrix.png?raw=true" width="600" height="500"/>

_Confusion matrix for the SVM._ 

<img src="images/confusion_matrix.png?raw=true" width="600" height="500"/>

_Confusion matrix for the Decision Tree Classifier._

<img src="images/confusion_matrix.png?raw=true" width="600" height="500"/>

_Confusion matrix for the KNN._

According to all the confusion matrices, all models produced the same result; their primary problem is false positives. That is, they predicted that the first stage of the rocket launch would land when, in fact, it did not.

### Hyperparameter Tuning

<img src="images/before_hyper.png?raw=true" width="600" height="500"/>

_Before hyperparameter tuning, all GridSearch algorithms were 83.3% accurate._

<img src="images/after_hyper.png?raw=true" width="600" height="500"/>

_After hyperparameter tuning, each GridSearch algorithm's accuracy improved by at least 1%. The Decision Tree Classifier model improved the most, having its accuracy enhanced by 4.2%._

From this project, it was concluded that the Decision Tree Classifier was the most accurate predictive model, yielding an 87.5% in accuracy.

_Please click on the buttons below for the full capstone presentation and the Jupyter notebook for this project._

<a href="https://richardlw14.github.io/sections/Richard Lung Wicaksono - IBM Data Science Capstone Presentation.pdf"><img src="images/PowerPoint_Logo_Image.jpg?raw=true" width="100" height="30"/></a>

<a href="https://richardlw14.github.io/sections/Machine Learning Prediction.ipynb"><img src="images/jupyter_logo.png?raw=true" width="100" height="30"/></a>

