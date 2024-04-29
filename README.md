# Early-Diabetes-Prediction

The goal of the project is to explore various ML models and find the best suited to predict diabetes with better accuracy. We experimented with various algorithms to predict diabetes. 

Dataset Description:
The data is gathered form Kaggle which is named as Pima Indian Diabetes Dataset. The dataset has many attributes of 768 patients.
Table 1: Dataset Description

<img width="369" alt="Screenshot 2024-04-29 at 9 34 58 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/cc6c272b-8f5f-41a0-82c7-982a3c8cb0ae">

The 9th attribute is the class variable of each data point. This class variable shows the outcome 0 and 1 for diabetics which indicates positive or negative for diabetics.

Distribution of Diabetic patients- We made a model to predict diabetes however the dataset was slightly imbalanced having around 500 classes labelled as 0 means negative means no diabetes and 268 labelled as 1 means positive means diabetic.

Data Pre-processing:
The most crucial process is data pre-processing. Missing values and other contaminants are common in healthcare data, which can reduce the data's efficacy. Data pre-processing is done to increase the quality and efficacy of the results obtained during the mining process. The method is critical for accurate results and good prediction when using Machine Learning Techniques on a dataset. Pre-processing is required in two steps for the Pima Indian diabetes dataset.
Removal of Missing Values: Remove all instances with a value of zero (0). It is impossible to have a value of zero. As a result, this instance is no longer valid. We make feature subsets by removing irrelevant features/instances, a process known as features subset selection, which minimises the dimensionality of data and allows us to work faster.
Splitting data- Data is standardised in training and testing the model once it has been cleaned. When the data is spewed out, we train the algorithm on the training data set while ignoring the test data set. The training model will be created using logic and algorithms, as well as the values of the feature in the training data. The goal of normalisation is to put all of the qualities on the same scale.

Apply Machine Learning

We use Machine Learning Technique after the data is ready. To predict diabetes, we apply a variety of classification and ensemble algorithms. The diabetes dataset of Pima Indians was used to test the approaches. The main goal is to use Machine Learning techniques to examine the performance of various methods and determine their accuracy, as well as to identify the responsible/important features that play a significant part in prediction.
Support Vector Machine (SVM): 
Support Vector Machine also known as SVM is a supervised machine learning algorithm. SVM is the most popular classification technique. SVM creates a hyperplane that separates two classes. It can create a hyperplane or set of hyperplanes in high dimensional space. This hyperplane can be used for classification or regression also. SVM differentiates instances in specific classes and can also classify the entities which are not sup- ported by data. Separation is done by through hyperplane that performs the separation to the closest training point of any class.


Logistic Regression: 

Logistic regression is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary).  Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables

Random Forest Classifier: 

An ensemble of decision trees is referred to as a Random Forest. We have a collection of decision trees (also known as "Forest") in Random Forest. Each tree assigns a categorization to a new object based on attributes, and we say the tree "votes" for that class. The classification with the highest votes is chosen by the forest (over all the trees in the forest).

Decision Tree Classifier: 

They can be used to solve both regression and classification problems. Decision tree uses the tree representation to solve the problem in which each leaf node corresponds to a class label and attributes are represented on the internal node of the tree.


Model Building

This is most important phase which includes model building for prediction of diabetes. In this we have implemented various machine learning algorithms which are discussed above for diabetes prediction.

Procedure of Proposed Methodology- 

Step 1: Import required libraries
Step 2: Import diabetes dataset.
Step 3: Pre-processing the data
Step 4: Machine Learning Modeling


Soft Voting Classifier

Soft voting involves adding up the probabilities of each prediction in each model and selecting the prediction with the highest total probability.

<img width="202" alt="Screenshot 2024-04-29 at 9 49 58 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/91cdd7f7-e88f-4d51-9133-a47f9c5b9d6e">

Important EDA : 

Raw Data Distribution : 

<img width="861" alt="Screenshot 2024-04-29 at 9 52 08 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/03ca950f-ac41-457b-b637-3eb95ef009a1">

Feature Correlation : 

<img width="863" alt="Screenshot 2024-04-29 at 9 54 08 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/610041e4-11a2-4576-bc6a-9799df6fc246">

Accuracy Comparison : 

<img width="245" alt="Screenshot 2024-04-29 at 11 25 43 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/9f67bcfc-9fe9-4aae-aba5-6f74965f1935">

Plot : 

<img width="293" alt="Screenshot 2024-04-29 at 11 26 16 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/483db732-2424-42dc-a9eb-e20bbb35cd5e">

Precision Comparison : 

<img width="254" alt="Screenshot 2024-04-29 at 11 27 05 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/ae09910e-c6ee-4784-8a29-7f040b6cbb34">
Plot : 

<img width="283" alt="Screenshot 2024-04-29 at 11 27 27 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/356fb263-faa0-468b-93fd-d4c089e3925d">

Recall Comparison : 

<img width="241" alt="Screenshot 2024-04-29 at 11 29 32 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/62ea773c-e273-4dae-ac5e-87826916b611">

Plot : 

<img width="287" alt="Screenshot 2024-04-29 at 11 31 38 PM" src="https://github.com/laasyaaprasad/Early-Diabetes-Prediction/assets/75083241/2c03c43a-9b3d-4acb-bd0c-4de51961d859">




