# Music on Mental Health
 
This is the repository for Music on Mental Health. The goal for this project is to explore how different music genres and listening habits can affect a person suffering from various mental health issues from the dataset. Based on the user’s mental issues, and demographics, train and test a model that informs the user if their favourite music genre is improving their mental health issues. The dataset is obtained through Kaggle: https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results

## Setup

#### Library Dependcies
- git clone https://github.com/mw1163528384/Music-on-Mental-Health.git
- cd Music-on-Mental-Health
- pip install -r requirements.txt

#### File Structure

The Code folder include.ipynb:
- data_process_analysis.ipynb: data understanding, data cleaning, data pre-processing and data visualization
- cnn_model.ipynb: CNN model
- CTGAN and Data Preprocessing.ipynb: expanding datset
- cnn_model_CTGAN.ipynb: CNN model using expanded datset
- mlp_model.ipynb: MLP model


The Data folder include:
- mxmh_survey_sesults.csv: The original Dataset
- data_cleaned.csv: the cleaned dataset
- encoded.csv: the processed dataset after cleaning
- data_cleaned_expand.scv: the cleaned dataset after expanding
- encodedCTGAN.csv: the processed dataset after expanding & cleaning
