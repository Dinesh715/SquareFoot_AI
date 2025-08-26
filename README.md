![SquareFoot AI](./assets/project-banner.jpeg)

# 🏠 SquareFoot AI : Real Estate Forecasting

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](LICENSE)

---

## 📖 Project Description
This project focuses on **predicting house prices in Bangalore** using **machine learning regression models**.  
The dataset contains details such as location, size, number of bedrooms, and total square footage.  

The workflow includes:  
- Data cleaning and preprocessing  
- Feature engineering (handling categorical and numerical data)  
- Model training and evaluation using **Linear Regression, Decision Trees, and Random Forests**  
- Comparing results to identify the best performing model  

The goal is to build a reliable **price prediction system** that can help buyers, sellers, and real estate professionals make **data-driven decisions** in the Bangalore housing market.  

---

## 📂 Project Structure
├── bangalore_price_prediction.ipynb # Jupyter Notebook with code

├── data/ # Dataset folder

├── bangalore_home_prices.csv # Input dataset

├── model/ # Saved trained models (optional)

├── visuals/ # Graphs and plots generated

├── README.md # Project documentation


---

## ⚙️ Requirements
- Python 3.x  
- Libraries:
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - jupyter  

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/bangalore-price-prediction.git
cd bangalore-price-prediction
```

Open the Jupyter Notebook:

```bash
jupyter notebook bangalore_price_prediction.ipynb
```

Run the notebook step by step to:

Load and preprocess the dataset

Train regression models

Evaluate accuracy and visualize results

📊 Example Output

Predicted house price for a given location and size

Visualization of price trends by location

Model performance comparison (Linear Regression vs Random Forest vs Decision Tree)

🌍 Use Cases

Helps buyers estimate fair property prices

Assists sellers in setting competitive prices

Useful for real estate companies to analyze market trends
