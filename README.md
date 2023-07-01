
# TITANIC SURVIVING PREDICTION
- This repository contains the code and data for a project on Titanic Surviving Prediction. The project uses the test.csv and train.csv dataset, which can be downloaded from Kaggle:https://www.kaggle.com/competitions/titanic/data
# Data Content
The data has been split into two groups:

* training set (train.csv)
* test set (test.csv)

* The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

* The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

### feature attributes:
* survival = Survival	/ 0 = No, 1 = Yes
* pclass = Ticket class / 1 = 1st, 2 = 2nd, 3 = 3rd
* sex=Sex	
* Age=Age in years	
* sibsp	= # of siblings / spouses aboard the Titanic	
* parch	= # of parents / children aboard the Titanic	
* ticket=Ticket number	
* fare	=Passenger fare	
* cabin	=Cabin number	
* embarked=Port of Embarkation
## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Sklearn
- Xgboost
- Lightgbm


- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn Xgboost Lightgbm
    
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

The analysis includes the following tasks:

- Data loading and cleaning
- Exploratory data analysis
- data visualization
- outlier detection 
- missing values
- preprocessing 
- building model
- evaluating model
- tuning model
- visualization the results


The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 
* In This Project, I built a model of Titanic Surviving Prediction with Gradient Boosting Classifier, XGBoost Classifier and Voting Classifier,LightGBM Classifier, RandomForest Classifer and AdaBoost Classifier after evaluating some classification algorithms. I have explored lots of insights by visualizing the dataset and I got precise result from model classification. According to my model, The R2  score is 0.79.

