# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: UTKARSH VISHWANATH PARULEKAR

*INTERN ID*:CT04DR2426

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

Task 4: Spam Email Classification using Machine Learning

Introduction

This project has been developed as part of the CODTECH Python Programming
Internship. Task 4 focuses on implementing a predictive machine learning
model using Scikit-learn to classify text data. For this task, a Spam Email
Classification system has been created to determine whether an email message
is spam or not spam (ham). Spam detection is one of the most common real-world
applications of machine learning and plays an important role in email security
and user experience.

The purpose of this task is to gain practical experience with the complete
machine learning workflow, including data preparation, feature extraction,
model training, evaluation, and prediction using Python libraries.

--------------------------------------------------------------------------

Objective

The main objectives of this task are:
- To understand the concept of supervised machine learning
- To implement a text classification model using Scikit-learn
- To convert text data into numerical features suitable for machine learning
- To train and evaluate a classification model
- To test the model with new and unseen email messages

--------------------------------------------------------------------------

Tools and Technologies Used

The following tools and technologies were used in this project:
- Python for implementing the machine learning logic
- Pandas for creating and handling the dataset
- Scikit-learn for model training and evaluation
- CountVectorizer for converting text into numerical feature vectors
- Multinomial Naive Bayes as the classification algorithm
- Jupyter Notebook for interactive coding and visualization of results

--------------------------------------------------------------------------

Dataset Description

A small text-based dataset was created for demonstration purposes. The dataset
consists of short email messages labeled as either spam or ham. Spam messages
include promotional and prize-related content, while ham messages represent
normal personal or informational communication. The text labels are converted
into numerical values so that the machine learning model can process them
effectively.

--------------------------------------------------------------------------

Model Implementation

The implementation of the model follows a structured workflow. First, the
dataset is loaded into a Pandas DataFrame and prepared for training. The data
is then split into training and testing sets to evaluate the model’s
performance on unseen data. Since machine learning models cannot directly
process text, the CountVectorizer technique is used to transform the text into
numerical features based on word frequency.

A Multinomial Naive Bayes classifier is trained using the vectorized training
data. This algorithm is well suited for text classification tasks due to its
simplicity and efficiency. After training, the model is evaluated using
accuracy score and a classification report to measure its performance.

--------------------------------------------------------------------------

Results and Output

The trained model is able to classify email messages as spam or not spam with
good accuracy on the sample dataset. The notebook displays evaluation metrics
and prediction results clearly. Additionally, the model is tested using a
custom email message to demonstrate real-time prediction capability. An output
screenshot has been included in the repository to show the final results.

--------------------------------------------------------------------------

Conclusion

This task demonstrates the practical application of machine learning concepts
for text classification using Scikit-learn. It provides hands-on experience in
building, evaluating, and testing a predictive model. The project successfully
fulfills the requirements of Task 4 of the CODTECH Python Internship and serves
as a foundational example of machine learning implementation in Python.

--------------------------------------------------------------------------

# OUTPUT 

<img width="1000" height="500" alt="Image" src="https://github.com/user-attachments/assets/dfcc9feb-0640-4287-8aa3-c3cfa1a8c5a1" />
