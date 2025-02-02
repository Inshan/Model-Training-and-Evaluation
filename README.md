Titanic Survival Prediction
This project implements supervised machine learning models to predict the survival of passengers on the Titanic. The models used for comparison are:

1. Logistic Regression
2. Random Forest
3. Neural Network (using TensorFlow)

The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

-Table of Contents
- A. Project Overview
- B. Dataset
- C. Installation
- D. Usage
- E. Results
- F. Key Findings

A. Project Overview
 - The goal of this project is to predict whether a passenger survived the Titanic disaster based on features such as age, gender, class, and fare. The project involves:

  1. Data preprocessing (handling missing values, encoding categorical variables).
  2. Splitting the dataset into training and test sets.
  3. Training and evaluating three machine learning models.
  4. Comparing the performance of the models.

B. Dataset
The dataset used in this project is the Titanic dataset, which contains information about 891 passengers. It includes the following features:

1. Survived: Whether the passenger survived (0 = No, 1 = Yes).
2. Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
3. Name: Passenger name.
4. Sex: Passenger gender.
5. Age: Passenger age.
6. SibSp: Number of siblings/spouses aboard.
7. Parch: Number of parents/children aboard.
8. Ticket: Ticket number.
9. Fare: Fare paid for the ticket.
10. Cabin: Cabin number.
11. Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

- The dataset is available at: (https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

C. Installation
- To run this project, you need to have Python installed along with the following libraries: (pandas, numpy, scikit-learn, Tensorflow)
- You can install the required libraries using pip: (Command: - pip install pandas numpy scikit-learn tensorflow)

D. Usage
Clone the repository:
- git clone https://github.com/Inshan/Model-Training-and-Evaluation.git
- cd Model-Training-and-Evaluation
- Run the Python script in jupyter notebook
- The notebook will load and preprocess the dataset, train and evaluate the three models, and display the performance metrics for each model.

E. Results
The performance metrics for each model are as follows:
- | Feature               | Model	Accuracy | Precision |	Recall |	F1-Score                                                           
- | Logistic Regression   |  0.7989	       |  0.7500   |	0.7121 |	0.7305                               
- | Random Forest         |  0.8212	       |  0.7778   |	0.7424 |	0.7597                               
- | Neural Network        | 0.8045	        | 0.7632	   | 0.7273 |	0.7449                                


F. Key Findings:
- Random Forest performs the best in terms of accuracy, precision, recall, and F1-score.
- Neural Network performs slightly better than Logistic Regression but requires more computational resources.
- Logistic Regression is a good baseline model but is outperformed by the other two models.

Thanks to the open-source community for providing the libraries used in this project.
