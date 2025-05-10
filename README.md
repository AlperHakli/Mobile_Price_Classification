# Mobile Price Prediction #

This project aims to predict the price range of mobile phones based on various features like battery, screen size, RAM, and other attributes. I applied several classification algorithms to predict the price category of the phones.


## Dataset ##

The dataset used in this project is the "Mobile Price Classification" dataset. It contains information about various mobile phone features such as:

- Battery Power
- Clock Speed
- RAM
- Screen Size
- Memory
- And other technical specifications

The target variable is the **price range** (classified into 4 categories).
## Algorithms Used ##

I applied several classification algorithms including Logistic Regression, Random Forest, and Support Vector Machines (SVM) to predict the mobile price range.
## Algorithms and Hyperparameter Optimization ##

For this project, I implemented several machine learning algorithms including:

- **Logistic Regression**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **Artificial Neural Networks (ANN)**

To optimize the performance of these models, I applied hyperparameter tuning techniques using:

- **GridSearchCV**: Exhaustive search over a specified parameter grid to find the best parameters.
- **RandomizedSearchCV**: A randomized search over the parameter space for more efficient optimization.
- **Hyperopt**: A library for optimizing hyperparameters with methods like random search and tree of Parzen estimators.
- **Optuna**: A framework for automating hyperparameter optimization using advanced techniques like Bayesian optimization.

These methods were applied to find the best parameters for each algorithm to improve classification accuracy.
## Evaulation ##
Lastly I evaulated best model with the roc curve


## Lets look at the notebook ##

![Image](images/Ekran ALıntısı.jpg)





















