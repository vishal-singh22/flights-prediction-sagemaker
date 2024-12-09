# Flight Prediction Using Amazon SageMaker

This project predicts flight delays using machine learning models built and trained on Amazon SageMaker. It includes data preprocessing, exploratory data analysis, model training, and visualization of predictions in an HTML report.

## Project Structure

├── data/ 
  │ ├── flight_data.csv # Dataset used for training and testing 
  │ ├── processed_data.csv # Cleaned and preprocessed dataset 
│ ├── notebooks/ 
    │ ├── data_analysis.ipynb # Exploratory Data Analysis (EDA) 
    │ ├── model_training.ipynb # Model training and evaluation 
    │ ├── sagemaker_deployment.ipynb # Deploying the model on SageMaker 
│ ├── outputs/   
    │ ├── analysis_report.html # HTML report of EDA and predictions 
│ ├── model_metrics.json # Model performance metrics 
│ ├── requirements.txt # Required Python packages 
├── README.md # Project documentation 
└── run.sh # Script to run the full pipeline
