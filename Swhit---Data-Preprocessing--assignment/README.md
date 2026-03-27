# Airbnb Data Analysis & Preprocessing (Python)

## 📌 Project Overview

This project performs exploratory data analysis (EDA) and preprocessing on Airbnb listing data to uncover insights and prepare the dataset for machine learning or analytical use.

---

## 🎯 Objective

The goal is to clean, analyze, and transform raw Airbnb data into a structured format that supports decision-making and modeling.

---

## 📊 Dataset

* Source: NYC Airbnb dataset
* Contains listing information such as:

  * Price
  * Location (latitude, longitude, neighborhood)
  * Room type
  * Reviews and availability

---

## 🧠 Analysis Workflow

### 1. Data Loading

* Imported dataset using pandas
* Inspected structure and initial records

### 2. Data Cleaning

* Handled missing values
* Removed or corrected invalid entries
* Standardized column formats

### 3. Feature Understanding

* Explored distributions of key variables:

  * Price
  * Room types
  * Neighborhood groups

### 4. Exploratory Data Analysis (EDA)

* Identified trends and patterns in pricing
* Compared room types and locations
* Analyzed review activity

### 5. Visualization

* Used matplotlib and seaborn to visualize:

  * Price distributions
  * Geographic patterns
  * Category comparisons

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📈 Key Insights

* Pricing varies significantly by neighborhood and room type
* Private rooms vs entire homes show distinct price distributions
* High-review listings often correlate with better pricing stability

---

## 💡 Business Relevance

This type of analysis can be used for:

* Pricing strategy optimization
* Market segmentation
* Investment decision-making (short-term rentals)
* Demand forecasting

---

## 🚀 How to Run

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
notebook/explore.ipynb
```

---

## 🔮 Future Improvements

* Build a price prediction model
* Add geospatial clustering
* Perform feature engineering for ML pipelines
* Deploy as an interactive dashboard (Streamlit)

---

## 👤 Author

Scott Whitfield
Data Analyst | Machine Learning Enthusiast
