# Cloud_Computing
Wildfire Forecasting Using NASA MODIS Data on AWS Cloud ☁️🔥

This project leverages NASA MODIS wildfire data (2003, 2013, 2023) to forecast fire trends using LSTM models and advanced feature engineering, all fully hosted on the AWS cloud ecosystem.

**Project Workflow**:

**Data Upload**: Uploaded wildfire CSV datasets to an AWS EC2 instance.

**Database Setup**: Created a free-tier RDS MySQL database to securely store the data.

**Data Ingestion**: Loaded the wildfire datasets into RDS via Python scripts running in a Jupyter Notebook hosted on EC2.

**Analysis & Modeling**:

Connected Jupyter to RDS to perform exploratory data analysis (EDA).

Engineered features such as month, year, location categories, and fire intensity levels.

Built and trained LSTM deep learning models to predict future wildfire trends.

Cloud-Native Workflow: All operations — from data storage to model training and evaluation — were executed entirely on AWS (no local resources used).

**Key Technologies**:
AWS EC2 (for Jupyter environment)

AWS RDS MySQL (for database storage)

Python (Pandas, NumPy, TensorFlow/Keras, SQLAlchemy)

Jupyter Notebook

LSTM (Long Short-Term Memory Neural Networks)

Feature Engineering (Temporal features, intensity scaling, normalization)

**Objective**:
To explore the temporal patterns in wildfire activity and build predictive models that could assist in early warning systems, resource planning, and climate impact studies.
