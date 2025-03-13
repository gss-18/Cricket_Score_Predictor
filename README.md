# 🏏 Cricket Score Predictor

Predict the first innings score in T20 cricket matches based on current match circumstances using machine learning techniques.

## 📈 Overview

This project aims to forecast the total runs a team will score by the end of their innings in a T20 match, given the current state of the game (e.g., runs scored, wickets lost, overs completed).

## 🗂️ Repository Structure

- **`Cricket_Score_Predictor.py`**: Main application script built with Streamlit to interactively predict scores.
- **`data_extraction.ipynb`**: Jupyter Notebook detailing the process of extracting and preprocessing raw cricket data.
- **`feature_extraction.ipynb`**: Notebook focusing on deriving meaningful features from the preprocessed data for model training.
- **`dataset_1/`**: Directory containing raw datasets used in the project.
- **`dataset_2.pkl`**: Serialized processed dataset ready for modeling.
- **`pipe.pkl`**: Saved machine learning pipeline, including preprocessing steps and the trained model.
- **`requirements.txt`**: List of Python dependencies required to run the project.
- **`image.jpg`**: Visual representation or logo related to the project.

## 🚀 Features

- **Interactive Prediction**: Utilize the Streamlit app to input current match details and receive immediate score predictions.
- **Data Processing**: Comprehensive notebooks detailing data extraction and feature engineering processes.
- **Model Deployment**: Pre-trained model available for direct use in predictions.
