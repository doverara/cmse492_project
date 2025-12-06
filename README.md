# Designing a Scalable Data Pipeline for Cyber Threat Detection

This project focuses on building a scalable end to end data pipeline for real time cyber threat detection using machine learning and network traffic analytics. The goal is to process raw network flow data, engineer meaningful features, and apply supervised learning models to identify patterns associated with anomalous or malicious activity.

The final pipeline includes data ingestion, preprocessing, feature engineering, exploratory analysis, and model training using Logistic Regression, Random Forest, and a Feedforward Neural Network. Random Forest achieved the strongest performance across accuracy, recall, and AUC-ROC, making it the most effective model for intrusion detection in this dataset.

Due to the size of the CICIDS-2017 dataset, only a small sample file is included in this repository; the full dataset must be downloaded separately. All figures, scripts, preprocessing steps, and notebook workflows are provided to ensure reproducibility of results.

## Directory Structure

**`data`** – Contains all datasets used in the project.  
- **raw** → Original unprocessed network traffic data.  
- **processed** → Cleaned and transformed datasets ready for analysis.  

**`docs`** – Stores written documentation, reports, and presentation materials.  

**`figures`** – Contains all plots, charts, and visualizations generated during exploratory data analysis or model evaluation.  

**`notebooks`** – Includes all Jupyter notebooks used for exploration and experimentation.  
- **exploratory** → Early-stage EDA, baseline models, and testing ideas.  

**`src`** – Holds all source code for the project pipeline.  
- **preprocessing** → Scripts for data cleaning and feature engineering.  
- **models** → Model training, tuning, and saving logic.  
- **evaluation** → Performance metrics, results generation, and comparison scripts.

## Setup instructions

**Clone the repository:**
- git clone git@github.com:doverara/cmse492_project.git
- cd cmse492_project
