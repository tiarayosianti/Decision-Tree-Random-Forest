# Predicting Marketing Success for Banks in Portuguese Banking Institutions Using Decision Tree and Random Forest


## Objective
This project aims to classify marketing data from Portuguese banking institutions to assist banks and marketing teams in predicting whether customers will subscribe to term deposit products. By identifying potential customers, banks can optimize marketing strategies and mitigate the risks of non-performing loans.


## Data
The project utilizes the [Bank Marketing Dataset](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing) from Kaggle. The dataset provides comprehensive information on marketing campaigns and customer responses, including customer demographics, campaign details, and previous interactions.


## Methodology

### 1. **Decision Tree**  
The Decision Tree algorithm uses the Gini Index for variable selection to determine the best features for splitting data at the root and subsequent nodes.

### 2. **Random Forest**  
Random Forest is an ensemble learning method that combines multiple decision trees.


## Results
- The **Decision Tree** method achieved an **F1-score of 0.95**, indicating strong classification performance.  
- The **Random Forest** method achieved an **F1-score of 0.56**, which was lower than that of the Decision Tree.  
- Based on the F1-score, the **Decision Tree** method outperformed the Random Forest, demonstrating its effectiveness in handling this classification task.
