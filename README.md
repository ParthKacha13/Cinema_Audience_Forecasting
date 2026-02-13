
---

## 🧠 Key Challenges

- Audience influenced by:
  - Holidays  
  - Weekends  
  - Theatre type  
  - Booking trends  
- Some theatres may be closed (zero audience days included)
- Anonymized location data (approximate latitude & longitude)
- Need to combine both POS and online booking behavior

---

## 🛠 Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Time-Series Feature Engineering  

---

## 🚀 Approach

### 1️⃣ Data Preprocessing
- Merging POS and BookNow datasets
- Handling missing values
- Processing date features
- Encoding categorical variables

### 2️⃣ Feature Engineering
- Extracting day of week, month, weekend flag
- Holiday impact modeling
- Aggregating historical booking trends
- Theatre-level performance metrics

### 3️⃣ Time-Series Modeling
- Lag features
- Rolling mean features
- Regression-based forecasting models

### 4️⃣ Model Training
- Linear Regression / Tree-based models
- Cross-validation on time-based splits

### 5️⃣ Submission Generation
- Predicting future audience counts
- Formatting output as per sample_submission.csv

---

## 📈 Key Insights

- Weekends and holidays significantly increase audience counts.
- Online booking trends strongly correlate with total attendance.
- Certain theatre types show consistent seasonal patterns.
- Zero-audience days correspond to closure days and are excluded from final scoring.

---

## 🎯 Conclusion

This project demonstrates practical application of time-series forecasting in real-world business scenarios. It highlights the importance of combining multiple data sources, feature engineering, and temporal modeling to generate reliable attendance predictions.

---

⭐ Feel free to explore the notebook and experiment with advanced models such as XGBoost, LightGBM, or LSTM for further improvements.
