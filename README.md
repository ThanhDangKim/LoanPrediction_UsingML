# LoanPrediction_UsingML
 21110298_21110175_FinalProjectML_v2

## Introduction
This project aims to predict which customers are likely to default on their consumer loans. The organization has historical data on customer behavior, which is used to predict the risk level of new customers. The goal is to identify high-risk customers early, allowing the organization to make informed decisions.

## About the Data
The dataset contains the following features:

- ID: Unique identifier for each user.
- Income: User's income.
- Age: User's age.
- Experience: User's professional experience in years.
- Profession: User's profession.
- Married/Single: User's marital status.
- House_Ownership: Whether the user owns a house, rents, or has no house ownership.
- Car_Ownership: Whether the user owns a car.
- STATE: User's state or territory of residence.
- CITY: User's city or area of residence.
- CURRENT_JOB_YRS: Number of years the user has been working at their current job.
- CURRENT_HOUSE_YRS: Number of years the user has been living at their current address.
- Risk_Flag: Target variable indicating whether the user has defaulted (1) or not (0).

## Project Structure
The project is organized as follows:

- 21110298_21110175_FinalProjectML.ipynb: The main Jupyter notebook containing the data exploration, preprocessing, modeling, and evaluation steps.
- README.md: This file, providing an overview of the project.

## Libraries Used
The following libraries are used in this project:

- numpy
- pandas
- seaborn
- matplotlib
- scipy
- imblearn
- scikit-learn

## Steps Involved
1. Data Exploration: Understanding the data, visualizing relationships, and identifying patterns.
2. Data Preprocessing: Handling missing values, encoding categorical variables, scaling numerical features, and addressing class imbalance using SMOTE.
3. Feature Engineering: Applying PCA for dimensionality reduction.
4. Modeling: Training and tuning various machine learning models to predict the risk of default.
5. Evaluation: Assessing model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

## How to Run the Project
1. Clone the repository.
2. Install the required libraries: pip install -r requirements.txt
3. Open the Jupyter notebook 21110298_21110175_FinalProjectML.ipynb and run the cells.

## Results
The results section will provide a detailed analysis of the model performance, including the confusion matrix, classification report, and AUC-ROC curves.

## Future Work
Potential improvements and further work include:

- Experimenting with additional machine learning algorithms.
- Fine-tuning hyperparameters for better model performance.
- Exploring additional features or external data sources to enhance the model.
  
## Contact us

- Contact me via email: dangkimthanh281003@gmail.com
