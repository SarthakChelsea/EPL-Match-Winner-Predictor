# **EPL Match Winner Prediction**  

## **Project Overview**  
This project aims to predict the winner of football matches in the English Premier League (EPL). By leveraging data scraping and machine learning techniques, we analyze historical match data to build a predictive model. The project demonstrates a complete data pipeline, from data acquisition and cleaning to modelling and evaluation.  

## **Problem Statement**  
Predicting the outcome of football matches is a challenging task due to the dynamic nature of sports events and complex influencing factors such as team form, player injuries, and venue advantages. This project addresses the problem by using machine learning models trained on historical data scraped from FBref to predict match outcomes (home win, away win, or draw).  

## **Results**  
The model achieved **67% accuracy** in predicting match outcomes by training on two years of historical EPL data. This demonstrates the potential of data-driven models in sports analytics, with room for improvement through feature engineering and hyperparameter tuning.  

## **Key Project Steps**  
1. **Data Scraping**:  
   - Extracted English Premier League match data using BeautifulSoup and requests from FBref.  
2. **Data Cleaning & Preparation**:  
   - Processed and cleaned match data using pandas to handle missing values, derive meaningful features, and structure the dataset.  
3. **Modeling & Prediction**:  
   - Trained machine learning models using scikit-learn to predict match outcomes.  
4. **Evaluation & Improvement**:  
   - Achieved 67% accuracy on test data, with further suggestions for optimization and refinement.  

## **Code Files**  
- `scraping.ipynb`: Scrapes match data from FBref.  
- `prediction.ipynb`: Builds and evaluates machine learning models for match outcome prediction.  

## **Local Setup**  
### **Installation**  
Ensure you have the following installed:  
- **JupyterLab**  
- **Python 3.8+**  
- Python packages:  
  - `pandas`  
  - `requests`  
  - `BeautifulSoup4`  
  - `scikit-learn`  

### **Data Acquisition**  
- To run the data scraping workflow, use `scraping.ipynb`.  
