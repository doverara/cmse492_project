# Designing a Scalable Data Pipeline for Cyber Threat Detection

This project focuses on building a scalable data pipeline capable of detecting cyber threats in real time by leveraging machine learning and network traffic analytics. The goal is to design an end-to-end workflow that ingests, preprocesses, and analyzes network data to identify patterns of anomalous or malicious activity.

In this initial phase, the project repository is being structured and the development environment is being configured. Future stages will involve data acquisition, preprocessing, model experimentation, and performance evaluation on simulated and real-world traffic datasets.

## Directory Structure

**data/** – Contains all datasets used in the project.  
- **raw/** → Original unprocessed network traffic data.  
- **processed/** → Cleaned and transformed datasets ready for analysis.  

**docs/** – Stores written documentation, reports, and presentation materials.  

**figures/** – Contains all plots, charts, and visualizations generated during exploratory data analysis or model evaluation.  

**notebooks/** – Includes all Jupyter notebooks used for exploration and experimentation.  
- **exploratory/** → Early-stage EDA, baseline models, and testing ideas.  

**src/** – Holds all source code for the project pipeline.  
- **preprocessing/** → Scripts for data cleaning and feature engineering.  
- **models/** → Model training, tuning, and saving logic.  
- **evaluation/** → Performance metrics, results generation, and comparison scripts.
