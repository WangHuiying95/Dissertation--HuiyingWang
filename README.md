This repository contains several files and scripts that correspond to different stages of data processing, analysis, and modeling as described below:

## 1. Dataset Information
The data used for this project is located in the file shared-files-HuiyingWang.txt. This dataset comprises two key components:

Dataset: Contains the source data files, including:
dataset+Dissertation: The primary data source.
review+Dissertation: The review data used in the analysis.

## 2. Preprocessing Steps
The preprocessing steps involved normalizing the data, handling case sensitivity, and applying stopwords filtering. Additionally, the preprocessing involved removing non-English content using regular expressions. The preprocessed data is saved in:

Preprocessed Data:
pre_progress_data+Dissertation: This file contains both the complete sentences and the preprocessed segments of the dataset.

## 3. M1 Model Results
The results of the aspect classification and sentiment analysis for Model 1 (M1) can be found in the following files. The analysis includes two models:

M1 SBERT Analysis: The code used for aspect and sentiment classification is in the M1 SBERT.ipynb notebook.
df_all_M1+Dissertation: Contains the final aspect classification and sentiment classification results using the SBERT model.
M1 LDA Analysis: The code for Latent Dirichlet Allocation (LDA) topic modeling is in the M1_LDA.ipynb notebook.

## 4. M2 Model Results
The results of the aspect classification and sentiment analysis for Model 2 (M2) are documented in the following files. The analysis includes two models:

M2 Pre-Clustering: The K-means clustering results used as input for further analysis are saved in cluster_df+Dissertation.
M2 SBERT Analysis: The code used for aspect and sentiment classification is in the M2 SBERT.ipynb notebook.
df_all_M2+Dissertation: Contains the final aspect classification and sentiment classification results using the SBERT model.
M2 LDA Analysis: The code for Latent Dirichlet Allocation (LDA) topic modeling is in the M2_LDA.ipynb notebook.

## 5. Confusion Matrix Data
The file Data_Label_merged_df_all_M1&M2_10000row+Dissertation contains a subset of 10,000 randomly selected rows that have been manually annotated. These annotations are used for the confusion matrix calculations to evaluate the model's performance.
