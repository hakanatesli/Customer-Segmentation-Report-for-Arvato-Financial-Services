# Customer-Segmentation-Report-for-Arvato-Financial-Services


## Project Motivation

In this project, we are provided with demographic data of customers of a mail-order company in 
Germany and demographic data of general population of Germany" Using this data, we are required to 
identify new customers for the company.


We approach this project in 2 phasese
* Use Unsupervised Learning to perform customer segmentation and identify clusters/segments 
from general population who best match mail-order company's customer base!
* Use Supervised Learning to identify targets for marketing campaign of the mail-order company 
who could possibly become their customers.


Goal of this project is to predict individuals who are most likely to become customers for a mail-order 
sales company in Germany"

## File Path

```
- Arvato Project Workbook.ipynb
- README.md
- LISENCE
- requirements.txt
```

## Installation

In order to run the project smoothly, you need to run the code below to download all the python libraries required at once.
```
pip install -r requirements.txt
```
PS: This project requires Python 3.x

## Data

The data has been provided by Udacity and Arvato Financial Solutions. But data used for this project not publically available. It was provided only to those participating in the "in class" competition.

## Technical Overview

Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we build preprocessing pipeline to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments. Due to the nature of the data (details in notebook), AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook:

* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Final Model Evaluation
* Feature Importance
* Analysis of identified important features in clusters to find relevance
* Scoring and submisstion to Kaggle

## Result

* In the first part, data evaluation and data preprocessing were performed. As in every data science project, we had a hard time in the data preprocessing phase. Some of the reasons we struggled: There were too many features and observations, some features were unexplained, some features had less missing data than they should have been.
* In the unsupervised part, dimensionality reduction was made using PCA to 194 latent features describing 95% of the explained variance. PCA was useful and it was good to see that the first three key components were able to distinguish seven clusters effectively.
* Finally, the Gradient Boosting Classifier was selected and parameterized to build the supervised model and make predictions on the test dataset on KAGGLE. The resulting performance of the supervised learning algorithm is 78.9%.

## Blog Post And Kaggle Competition
Medium - https://hakanateslii.medium.com/customer-segmentation-for-financial-services-58fbfc417669

Kaggle - https://www.kaggle.com/hakanatesli/competitions


## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Hakan ATEŞLİ - [@hakanatesli](https://www.linkedin.com/in/hakanatesli/) - hakanatesli9000@gmail.com
