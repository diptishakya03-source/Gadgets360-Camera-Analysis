# Gadgets360 Camera Analysis

## Project Overview
This project performs end-to-end Exploratory Data Analysis (EDA) and Machine Learning on camera specifications data sourced from Gadgets360 via Kaggle.
It showcases practical data cleaning, visualization, feature engineering, and ML modeling skills using Python and Jupyter Notebook.
Designed as a resume/portfolio project for a BSc Data Science student.

---

## Objectives
Understand and clean real-world product specification data
Analyze relationships between price, brand, ratings, and technical features
Visualize market trends and feature distributions
Build ML models to analyze and predict camera pricing patterns

---

## Dataset
Source: Kaggle (Gadgets360 Camera Dataset)
Content Includes:
Brand & model details
Price in India
Ratings
Camera specifications (sensor type, ISO, zoom, video resolution, display, etc.)
 Dataset Link:
https://www.kaggle.com/datasets/deepann/4000-laptops-data-from-gadgets360
 Used strictly for educational and portfolio purposes. All credits belong to the dataset creator.

---

### Key Features
- Brand, Model, Color
- Price in India
- Camera specifications (sensor type, ISO, zoom, display size, etc.)
- User ratings (1 to 5 stars)

Each row represents a unique camera model with its specifications and ratings.

---

## Tools & Technologies
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn

---

## Exploratory Data Analysis (EDA)
The following analyses were performed:
- Price distribution of cameras
- Brand-wise product comparison
- Relationship between price and user ratings
- Market segmentation using price categories
- Correlation analysis between numerical features

---

## Feature Engineering
- Cleaned price values by removing currency symbols
- Created an **Average Rating** feature using star ratings
- Handled missing values using median and mode
- Created a new feature **Price_Category**:
  - Budget (< ₹30,000)
  - Mid-range (₹30,000 – ₹70,000)
  - Premium (> ₹70,000)

---

## Machine Learning Models

### Regression (Price Prediction)
- Linear Regression
- Random Forest Regressor

**Evaluation Metrics:**
- R² Score
- RMSE

### Classification (Price Category Prediction)
- Random Forest Classifier

**Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-score

Random Forest models performed better due to non-linear relationships between features.

---

## Key Insights
- Brand and camera specifications significantly impact pricing
- Premium cameras form a smaller but high-value segment
- Higher price does not always guarantee higher ratings
- Feature engineering using star ratings improved model performance

---

## Conclusion
This project showcases practical data analysis and machine learning skills
using a real-world, unstructured dataset. It reflects the ability to clean,
analyze, and model complex data effectively.

---

## Author
Dipti Shakya
BSc Computer Science(Data Science) Student | India
