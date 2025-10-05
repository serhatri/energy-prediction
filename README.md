# Appliances Energy Prediction

Predicting household appliances' energy consumption using the **UCI Appliances Energy Prediction dataset**.

## Project Overview

This project focuses on forecasting household appliance energy usage based on environmental and operational data.  
The workflow involves:

- Exploratory Data Analysis (EDA)
- Pearson correlation-based feature selection
- Incremental linear regression models (1–10)
- Model evaluation using MSE & MAPE (70/30 train-test split)
- Selecting the best-performing model

## Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Jupyter  

## Folder Structure

data/ # Dataset and any preprocessed files
notebooks/ # Jupyter notebooks for analysis and modeling
src/ # Python scripts (if modularized)
results/ # Generated figures, performance metrics, and outputs


## Results

- Identified top 10 most influential features using Pearson correlation  
- Built 10 incremental regression models with increasing feature sets  
- Compared models using MSE and MAPE metrics  
- Selected the optimal model based on performance and parsimony

## License

This project is open-source and available under the [MIT License](LICENSE).
