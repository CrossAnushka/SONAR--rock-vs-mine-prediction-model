# Sonar Rock vs Mine Classification

This mini project uses a machine learning model to classify sonar signals as either **rock** or **mine** based on sonar returns. The dataset used contains 208 samples with 60 features each, representing sonar signal returns.



## Machine Learning Model Used
For this classification task, we used Logistic Regression, a simple yet powerful linear model suitable for binary classification problems like this one (rock vs. mine).

Why Logistic Regression?
	•	Binary Output: Logistic Regression is ideal for problems with two output classes — in this case, detecting either a Rock (0) or a Mine (1).
	•	Efficient for Linearly Separable Data: Since the sonar dataset shows a reasonable separation between classes in some dimensions, logistic regression performs well.
	•	Fast and Lightweight: It trains quickly and requires less computational power compared to more complex models like neural networks or ensemble methods.


The notebook covers:
	•	Data exploration and preprocessing
	•	Train-test splitting
	•	Model building using Logistic Regression 
	•	Accuracy and performance evaluation

