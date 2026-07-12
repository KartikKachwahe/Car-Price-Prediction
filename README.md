# 🚗 Ford Car Price Prediction Model

---

<p align="center">

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-0099CC?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Application-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</p>

<p align="center">
<b>An end-to-end Machine Learning project that predicts the resale price of Ford cars using vehicle attributes and supports data-driven pricing decisions for buyers, sellers, and dealerships.</b>
</p>

---

# Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Tech Stack](#-tech-stack)
- [Project Workflow](#-project-workflow)
- [Data Preprocessing](#-data-preprocessing)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Feature Description](#-feature-description)
- [Model Development](#-model-development)
- [Model Evaluation](#-model-evaluation)
- [Prediction System](#-prediction-system)
- [How To Run](#-how-to-run)
- [Repository Structure](#-repository-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Enhancements](#-future-enhancements)
- [Business Impact](#-business-impact)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

#  Project Overview

The used car market is growing rapidly, and pricing a car correctly is critical for both buyers and sellers. Overpriced listings sit unsold, while underpriced ones cause sellers to lose money.

This project uses Machine Learning techniques to analyze Ford car listings and predict the resale price of a vehicle based on its specifications and condition.

The project combines:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- Machine Learning model training
- Model evaluation
- Model deployment

The system helps:

- Estimate a fair resale price for a Ford car
- Support pricing decisions for sellers and dealerships
- Help buyers avoid overpaying
- Identify which features drive car value the most

---

#  Business Problem

Car buyers and sellers often struggle to determine a fair market price for a used vehicle.

Traditional pricing approaches can:

- Rely on subjective dealer judgment
- Be inconsistent across sellers and platforms
- Ignore the combined impact of multiple vehicle attributes
- Lead to overpriced or underpriced listings

Key questions addressed:

- Can Machine Learning accurately predict the price of a used Ford car?
- Which vehicle attributes influence price the most?
- Can predictive analytics support fairer pricing decisions?
- How can data-driven pricing improve buyer and seller confidence?

---

#  Project Objectives

### Business Objectives

- Predict the resale price of a Ford car
- Analyze how vehicle attributes affect price
- Identify important predictive features
- Train and evaluate regression models
- Build a prediction system
- Support data-driven pricing decisions

---

#  Dataset Information

**Dataset Source:** Ford Used Car Listings Dataset (Kaggle)

### Dataset Summary

| Metric | Value |
|----------|--------|
| Total Records | *(update with actual row count)* |
| Total Features | *(update with actual feature count)* |
| Target Variable | Price |
| Data Type | Structured Tabular Data |

---

### Features Included

| Feature | Description |
|-----------|-------------|
| model | Ford car model name |
| year | Year of manufacture/registration |
| price | Selling price of the car (Target) |
| transmission | Type of transmission (Manual/Automatic/Semi-Auto) |
| mileage | Total distance driven (in miles) |
| fuelType | Type of fuel (Petrol/Diesel/Hybrid/Electric) |
| tax | Road tax amount |
| mpg | Miles per gallon (fuel efficiency) |
| engineSize | Engine capacity (in litres) |

*(Update the feature list above to match the exact columns in your dataset.)*

---

#  Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |
| Scikit-Learn | Machine Learning |
| Streamlit | Web Application |
| Pickle | Model Serialization |
| Git/GitHub | Version Control |

---

#  Project Workflow

```text
Raw Dataset (.CSV)
          │
          ▼
Data Preprocessing
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Train-Test Split
          │
          ▼
Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Model Serialization
(.pkl)
          │
          ▼
Prediction Web Application
```

---

#  Data Preprocessing

Data preprocessing was performed before model development.

### Tasks Performed

- Imported dataset
- Checked missing values
- Removed duplicates
- Handled categorical variables (encoding)
- Outlier detection and treatment
- Feature scaling
- Train-test splitting
- Data transformation

---

#  Exploratory Data Analysis

Exploratory analysis was conducted to understand relationships between vehicle attributes and price.

### Analysis Performed

- Distribution Analysis
- Correlation Analysis
- Price vs. Feature Relationships
- Model-wise Price Trends
- Fuel Type and Transmission Impact Analysis

### Key Observations

- Car age and mileage significantly affect resale price
- Engine size and fuel type influence pricing patterns
- Transmission type shows a noticeable impact on value
- Newer cars with lower mileage retain higher resale value

---

#  Model Development

Machine learning workflow:

- Data splitting
- Feature scaling / encoding
- Model training
- Hyperparameter tuning
- Performance evaluation

### Model Pipeline

```python
Dataset
   ↓
Train-Test Split
   ↓
Feature Encoding & Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Performance Evaluation
```

---

#  Model Evaluation

Model performance was evaluated using regression metrics.

### Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Goals

- Improve prediction accuracy
- Minimize prediction error
- Increase model generalization on unseen data

---

#  Prediction System

Users provide car specifications and receive an estimated price.

### Prediction Flow

```text
User Inputs Car Details
              │
              ▼
Preprocessing
              │
              ▼
Trained ML Model
              │
              ▼
Prediction
              │
              ▼
Estimated Car Price
```

---

#  How To Run

### Clone Repository

```bash
git clone https://github.com/KartikKachwahe/Car-Price-Prediction.git
```

### Move into Project Directory

```bash
cd Car-Price-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit App

```bash
streamlit run app.py
```

---

#  Repository Structure

```text
Car-Price-Prediction
│
├── Pickel files
│   ├── model.pkl
│   └── scaler.pkl
│
├── Car-Price-Prediction.ipynb
├── app.py
├── ford.csv
├── README.md
```

---

#  Skills Demonstrated

### Python

- Data Cleaning
- Data Manipulation
- Feature Engineering

### Machine Learning

- Regression Models
- Model Training
- Model Evaluation
- Predictive Analytics

### Data Science

- Exploratory Data Analysis
- Automotive Market Analytics
- Data Visualization

### Software Development

- Model Deployment
- Pickle Serialization
- Git Version Control

---

#  Future Enhancements

- Deploy application to cloud
- Add datasets from other car brands for comparison
- Implement advanced ensemble/boosting models
- Build an interactive pricing dashboard
- Add Explainable AI (XAI) for feature impact
- Improve prediction interpretability

---

#  Business Impact

Potential business benefits:

✅ Fair and consistent price estimation

✅ Better decision-making for buyers and sellers

✅ Reduced pricing guesswork for dealerships

✅ Faster listing and valuation process

✅ Improved market transparency

✅ Data-driven pricing strategy

---

#  Conclusion

This project demonstrates how Machine Learning can support the automotive resale market by predicting Ford car prices using vehicle attributes.

The project covers a complete end-to-end Data Science workflow:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- Machine Learning model development
- Performance evaluation
- Deployment-ready prediction system

Predictive pricing solutions can help improve transparency and support better decision-making in the used car market.

---

# 👨‍💻 Author

## Kartik Kachwahe

**Aspiring Data Scientist | Data Analyst | Machine Learning | SQL | Power BI | Python**

📧 Email: kartikkachwahe25@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/kartikkachwahe021

💻 GitHub: https://github.com/KartikKachwahe

---

## ⭐ Support

If you found this project useful, consider giving the repository a star.

Your support motivates future projects and helps others discover this work.

---

**Thank you for visiting this repository 🚗**
