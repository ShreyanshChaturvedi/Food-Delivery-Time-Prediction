# 🛵 Food Delivery Time Prediction

## 📌 Objective
This project aims to **predict food delivery times** based on multiple features like customer and restaurant location, weather conditions, traffic, vehicle type, and more. It covers data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling using **Linear Regression** and **Logistic Regression**.

---

## 📁 Dataset
**File:** `Food_Delivery_Time_Prediction.csv`  
The dataset includes:
- Distance between restaurant and customer
- Delivery Time
- Weather and Traffic Conditions
- Order Cost
- Vehicle Type
- Delivery Person Experience
- Order Priority

---

## 🔎 Phase 1: Data Preprocessing & EDA

### ✅ Step 1: Data Cleaning & Encoding
- Handled missing values in key columns (`Distance`, `Delivery_Time`, etc.).
- Encoded categorical features using Label Encoding and One-Hot Encoding.
- Normalized continuous features (`Distance`, `Order_Cost`, `Delivery_sTime`).

### 📊 Step 2: Exploratory Data Analysis
- Performed descriptive statistics (mean, median, variance, etc.).
- Analyzed correlations with `Delivery_Time`.
- Detected outliers using boxplots and visual inspections.

### 🛠️ Step 3: Feature Engineering
- Calculated distance using Haversine formula (if coordinates were provided).
- Created time-related features like `Rush_Hour` to enhance model accuracy.

---

## 🤖 Phase 2: Predictive Modeling

### 📈 Linear Regression
- Split data (80% training, 20% testing).
- Used Linear Regression to predict exact delivery times.
- **Evaluation Metrics:**
  - R-squared (R²)
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)

### ⚖️ Logistic Regression
- Classified deliveries into `"Fast"` or `"Delayed"`.
- Trained a Logistic Regression model using traffic, weather, and experience as features.
- **Evaluation Metrics:**
  - Accuracy
  - Precision & Recall
  - F1-score
  - Confusion Matrix

---

## 📊 Model Comparison & Insights

- Compared models using confusion matrices, ROC curves, and regression metrics.
- Visualized findings using:
  - Pairplots
  - Heatmaps
  - Boxplots
  - Confusion Matrices

---

## 💡 Actionable Insights
- Optimize delivery routes based on peak traffic hours.
- Increase staffing during high-demand times.
- Provide additional training to improve delivery efficiency.

---

## 🚀 Final Deliverables

| File/Folder       | Description                                |
|-------------------|--------------------------------------------|
| `notebooks/`      | Jupyter notebook with full code & analysis |
| `data/`           | Dataset file (`.csv`)                      |
| `images/`         | Visualizations (optional)                  |
| `README.md`       | Project overview and documentation         |
| `requirements.txt`| (Optional) Python dependencies             |

---

## 🛠 Tools & Libraries Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Scikit-learn for modeling
- Git & GitHub for version control

---

## 📬 Contact
For questions or collaborations, feel free to open an issue or reach out via [GitHub](https://github.com/).

---

⭐ If you like this project, give it a star on GitHub!
