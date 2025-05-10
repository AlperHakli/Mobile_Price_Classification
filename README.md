# Mobile Price Prediction 

This project aims to predict the price range of mobile phones based on various features like battery, screen size, RAM, and other attributes. I applied several classification algorithms to predict the price category of the phones.


## Dataset 

The dataset used in this project is the "Mobile Price Classification" dataset. It contains information about various mobile phone features such as:

- Battery Power
- Clock Speed
- RAM
- Screen Size
- Memory
- And other technical specifications

The target variable is the **price range** (classified into 4 categories).
## Algorithms Used 

I applied several classification algorithms including Logistic Regression, Random Forest, and Support Vector Machines (SVM) to predict the mobile price range.
## Algorithms and Hyperparameter Optimization 

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
## Evaulation 
Lastly I evaulated best model with the roc curve


# Lets look at the notebook 

### Features and Explanation 
<img src="images/Ekran%20Alıntısı.JPG" alt="Ekran Alıntısı" width="400" />

### Number of Samples
<img src="images/Ekran%20Alıntısı2.JPG" alt="Ekran Alıntısı" width="300" />

#### A plot displaying the individual counts for each type in the feature
<img src="images/Ekran%20Alıntısı3.JPG" alt="Ekran Alıntısı" width="300" />

### Correlation Map with Heatmap
<img src="images/Ekran%20Alıntısı4.JPG" alt="Ekran Alıntısı" width="300" />

### Accuracy rate of different algorithms
<img src="images/Ekran%20Alıntısı5.JPG" alt="Ekran Alıntısı" width="300" />

### Accuracy of tuned logistic regression with gridsearch
<img src="images/Ekran%20Alıntısı7.JPG" alt="Ekran Alıntısı" width="350" />

### Accuracy of tuned randomforestclassifier with randomizedsearch

<img src="images/Ekran%20Alıntısı8.JPG" alt="Ekran Alıntısı" width="400" />

### Accuracy of tuned randomforestclassifier with hyperopt
<img src="images/Ekran%20Alıntısı9.JPG" alt="Ekran Alıntısı" width="400" />























