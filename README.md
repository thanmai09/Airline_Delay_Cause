# ✈️ Airline Delay Cause Analysis  
A simple and beginner-friendly **Exploratory Data Analysis (EDA)** project performed on the **Airline Delay Cause dataset** from Kaggle.  
This project includes **univariate analysis, bivariate analysis, visualizations**, and insights about different delay causes.

---

## 📌 Dataset
**Kaggle Link:**  
[Airline Delay Cause Dataset](https://www.kaggle.com/datasets/abdelazizel7or/airline-delay-cause)

The dataset contains information about:
- Arrival delays  
- Carrier delays  
- Weather delays  
- NAS delays  
- Security delays  
- Late aircraft delays  
- Months of travel  
- Other flight factors  

---

## 🎯 Project Objective
The main goal of this project is to understand:
- How often flights get delayed  
- What causes the delays  
- Which delay reason contributes the most  
- How delays vary across months  
- Relationships between delay types and arrival delay  

This project is designed to help beginners practice **basic EDA techniques** using Python.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📂 Project Structure
```
Airline_Delay_Cause/
│
├── Airline_Delay_Cause.ipynb    # Jupyter Notebook with analysis
├── README.md                    # Project documentation
└── Airline_Delay_Cause.csv      # Dataset (if uploaded)
```

---

# 📊 Analysis Performed

## 🔹 1. Univariate Analysis
Examines each feature independently.

### Performed on:
- **Arrival Delay (ArrDelay)** – Histogram  
- **Month** – Bar chart of flight count  
- **Delay Causes** (Carrier, Weather, NAS, Security, Late Aircraft) – Total delay comparison  

### Sample Visuals:
- Histogram  
- Bar plot  
- Summary statistics  

---

## 🔹 2. Bivariate Analysis
Shows relationships between two variables.

### Performed on:
- **Month vs Avg Arrival Delay** – Line plot  
- **Carrier Delay vs Arrival Delay** – Scatter plot  
- **Weather Delay vs Arrival Delay** – Scatter plot  
- **NAS Delay vs Arrival Delay** – Scatter plot  

These help identify patterns like:
- Which months have higher delays  
- Which delay cause affects arrival delay the most  

---

# 📉 Key Insights
- Some delay causes contribute far more to overall delay times.  
- Arrival delays show clear variability across months.  
- Positive relationships are seen between certain delay causes and arrival delay (e.g., carrier & weather delays).

---

# ▶️ How to Run the Project

### 1. Clone the repository  
```bash
git clone https://github.com/thanmai09/Airline_Delay_Cause.git
```

### 2. Install necessary libraries  
```bash
pip install pandas matplotlib
```

### 3. Open the notebook  
```bash
jupyter notebook Airline_Delay_Cause.ipynb
```

---

# 📝 Conclusion
This project provides a simple and clear understanding of airline delays using:
- Summary statistics  
- Easy visualizations  
- Beginner-friendly EDA steps  

It helps build strong foundations for:
- Data cleaning  
- Univariate & bivariate analysis  
- Visualization using matplotlib  

---

# ⭐ Future Improvements
You can extend the project by adding:
- Multivariate analysis  
- Time-series analysis  
- Dashboard using PowerBI or Tableau  
- Predicting delays using ML models  

---

# 👍 Author
**Thanmai Sree Macharla**

