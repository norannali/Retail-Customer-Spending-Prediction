#  Customer Spending Prediction Using Linear Regression

This project analyzes retail transaction data to predict **total customer spending** using behavioral indicators such as **Recency, Frequency, and Monetary value (RFM)**. It combines rigorous data preprocessing, smart feature engineering, and model evaluation to deliver actionable business insights.


## 📊 Summary of Results

- **Linear Regression** achieved **R² = 0.91**, explaining 91% of the variance in customer spending.
- **Transaction frequency** (`NumTransactions`) was the strongest predictor (~$100 per transaction).
- **Random Forest** outperformed Linear Regression with **R² = 0.94** and **MAE = $106**.
- **RFM-based feature engineering** (Recency, Frequency, Monetary) significantly improved prediction accuracy.

## ⚙️ Workflow

1. **Data Cleaning**: Removed nulls, duplicates, and cancellations.
2. **Feature Engineering**:
   - `Recency`: Days since last transaction
   - `Frequency`: Number of unique transactions
   - `Monetary`: Total spending per customer
3. **Exploratory Data Analysis**: Outlier detection, correlation heatmap, distribution plots
4. **Modeling**: Linear Regression and Random Forest Regressor
5. **Evaluation**: R², MAE, MSE, and actual vs. predicted visualizations
6. **Bonus**: Interactive prediction function for business use

##  Key Features

- ✅ Clean and reproducible code
- ✅ RFM-based behavioral modeling
- ✅ Visual insights (heatmaps, prediction plots)
- ✅ Business-focused summary and interpretation
- ✅ Model comparison for performance benchmarking

##  Business Value

This solution empowers businesses to:

- Identify **high-value customers**
- Perform **targeted marketing**
- Forecast **future revenue** with high confidence

##  Future Improvements

- Explore **ensemble models** for higher accuracy
- Add **hyperparameter tuning**
- Integrate **additional customer attributes** (e.g., geography, device usage)

##  Deliverables

- 📒 Jupyter Notebook with full analysis
- 📊 Visualizations and evaluation metrics
- 📝 Business-focused insights and recommendations

---

### 📬 Contact

**[Noran Ali Elsaeid]**  
📧 noranali322@gmail.com
📍 GitHub: (https://github.com/noranali)


