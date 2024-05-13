Mineral Resource Management Project

Overview

This project aims to leverage machine learning techniques for effective management of mineral resources by providing insights into operational mines and their locations. The dataset used in this project contains information about various features related to mines, such as geographical coordinates, mine types, and operational details.

Dataset Description

Feature Selection: Relevant features were selected based on their potential impact on predicting mine types.

FEATTYPE: The type of feature represented by the data point.
SECCLASS: The security classification of the mine.
STATE: The state where the mine is located.
ZIP/ZIPP4: The ZIP code/ZIP+4 code of the mine's location
COUNTY and FIPS codes provide county-related information for better understanding
NAICSDESCR: This column provides a description of the industry classification for each mine. This can give insights into the specific type of mineral resource extraction taking place in different mines.
MINE_TYPE: This column indicates the type of mine (e.g., coal, gold, copper, etc.)

Preprocessing

Data Cleaning: Missing values were handled, and categorical features were encoded using label encoding techniques.

Model Building

XGBoost Classifier: A machine learning model was trained using the XGBoost algorithm to predict mine types based on the selected features.
Evaluation Metrics: The model's performance was evaluated using accuracy, precision, recall, and F1-score. Additionally, feature importance analysis was conducted to understand the contribution of each feature to the model's predictions.

Results

Model Performance: The XGBoost model achieved an accuracy of 95.67% on the test dataset, indicating its effectiveness in predicting mine types.
Feature Importance: NAICSDESCR (description of minerals being extracted) emerged as the most important feature for predicting mine types, followed by geographical features such as ZIP code, county, and coordinates.

Next Steps

Further fine-tuning of the model parameters to improve performance.
Exploration of other machine learning algorithms and ensemble methods.
Collection of additional data sources to enhance model predictions.
Deployment of the model for real-world applications in mineral resource management.

Acknowledgements 

Source: The dataset was obtained from Kaggle and is available at Operational Mineral Resource Mines Dataset.
https://www.kaggle.com/datasets/thedevastator/operational-mineral-resource-mines
License: The dataset is provided under the Creative Commons Attribution 4.0 International License.
https://creativecommons.org/licenses/by/4.0/
