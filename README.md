# 🎥 Cinema_Audience_Forecasting

Time-Series Forecasting of Daily Cinema Audience Attendance

## 📊 Dataset
Provided by Competition Platform  
- cinePOS_theaters.csv  
- booknow_theaters.csv  
- movie_theater_id_relation.csv  
- cinePOS_booking.csv  
- booknow_booking.csv  
- booknow_visits.csv  
- date_info.csv  
- sample_submission.csv  

## 🛠 Tools Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

## 🚀 Approach
- Data Merging (POS + Online Booking Data)  
- Date & Holiday Feature Extraction  
- Lag & Rolling Features for Time-Series  
- Model Training (Regression-Based Models)  
- Time-Based Validation  
- Submission File Generation  

## 🎯 Target
Predict daily `audience_count`  
(ID = book_theater_id + show_date)

## 📈 Key Factors Considered
- Weekend & Holiday Impact  
- Online vs POS Booking Trends  
- Theatre Type & Location  
- Historical Attendance Patterns  
