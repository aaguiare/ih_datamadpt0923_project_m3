<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

## **Ironhack Data PT MAD - Project Module 3**

This README file includes the details of the repository elements required for the module 3 project within Data Analytics Bootcamp in Ironhack Madrid.
The project consists of training a model to get to the most accurate price prediction based on a training dataset towards a test dataset, being all uploaded to a priavate Kaggle competition. 

**Data**

- SQL database with diamonds training data 
- CSV downloaded from SQL analysis with diamonnds training data
- CSV with diamonds test data to set as base for price prediction

**Resources in this repository**

This repository will include the following elements (apart from the ones defined in **Data**): 

- All the different results achieved with model testing and fine tuning, in the folder "Delivery"
- All the different appraoches to model testing in Jupyter notebooks, allocated in the folder "main" 
```

📁 Folder structure
└── project
    ├── README.md
    ├──.gitignore    
    ├── main
    ├── deliveries
    └── data
        ├── diamonds_train.csv
        ├── diamonds_test.csv
        ├── diamonds_train.db
        ├── sample_submission.csv


```

💥**Technology stack**

Phyton, Scikit Learn

👀**Context**

This repository is the final project for Module 3 project for the Part Time Data Analytics Bootcamp in February 2024, which had the following requirements: 

The goal of this competition is the prediction of the price of diamonds based on their characteristics (weight, color, quality of cut, etc.). This is an academic competition created for the students of the Ironhack Data Analytics Bootcamp.

Challenge link https://www.kaggle.com/competitions/ihdatamadpt0923projectm3

💣 **Reporting Architecture**

1. Data Extraction:

Downloaded the dataset from Kaggle into my desktop. 
With DBeaver, extracted the CSV to work with using SQL, as it was in db. 
Imported both training and testing dataset. 
Import Libraries: Loading necessary Python libraries ( pandas, numpy, sklearn).


2. Data Exploration and Cleaning:

Exploring data distributions, missing values, and outliers.
Cleaning data by filling in missing values, removing outliers, and correcting errors.

3. Feature Engineering:

Creating new features from existing data with Label Encoding towards "Price", selecting relevant numbers for categorical features.
Selecting or extracting relevant features for the model.

4. Data Preprocessing:

Normalizing or standardizing numerical features.
Scaling data for standarized data weight with StandardScaler.

5. Model Selection:

Choosing appropriate machine learning models for the task (regression, classification, clustering).

6. Model Training:

Splitting data into training and testing sets.
Training selected models on the training dataset.
Trained both Linear Regression and Random Forest for model comparation.

7. Model Evaluation:

Evaluating model performance using MSE, RMSE as for regression process, where Random Forest was the most efficient one.
Using cross-validation for more robust evaluation.

8. Hyperparameter Tuning:

Adjusting model parameters to improve performance.
Using techniques like Grid Search or Randomized Search.

9. Model Deployment:

Preparing the model for deployment in the test dataseset for price prediction.

💩 **ToDo**

As next steps and continuous improvements: 

- Improve fine tuning to more accurate results in price prediction


💌 **Contact info**

Hi! I am Ana! 🎟
Feel free to contact me at teamurjc@gmail.com. Happy to chat!