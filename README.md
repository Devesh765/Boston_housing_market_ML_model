# 🏡 Housing Price Prediction using Linear Regression

This project predicts housing prices in Boston using a **Linear Regression** model. It explores the relationship between housing prices and various features like crime rates, average number of rooms, and socio-economic factors.

## 📊 Data Cleaning
- Managed missing data (3.95% missing per column)
- Treated outliers in key features (CRIM, ZN, RM) for data integrity

## 🔍 Feature Engineering
- Scaled features using **StandardScaler**
- Reduced multicollinearity with **VIF analysis**
- Dropped highly correlated variables like **RAD** to optimize model inputs

## 🤖 Model Building
- Built a **Linear Regression** model
- Achieved an **R² score of 0.797** on the test data

## 📈 Insights
- **RM (average rooms)** positively impacts housing prices
- **LSTAT (lower socioeconomic status)** shows a strong negative correlation with prices

## 🚀 Skills Demonstrated
- **Data Cleaning**: Handling missing values, outlier treatment
- **Feature Engineering**: Scaling, VIF analysis, feature selection
- **Machine Learning**: Linear Regression model building
- **Model Evaluation**: R², performance metrics
- **Data Visualization**: Visualizing trends and insights

## 🔧 Technologies Used
- **Python**: For data processing and model building
- **Scikit-learn**: For machine learning algorithms
- **Pandas**: For data manipulation
- **Matplotlib/Seaborn**: For data visualization

## 📈 Project Results
- The model achieved an **R² score of 0.797**, indicating that it can predict housing prices with good accuracy based on the selected features.

## 🚀 Future Work
- Exploring more advanced regression models like **Random Forest** or **XGBoost** for improved accuracy.
- Incorporating more features (e.g., location, amenities) for better predictions.

---

Feel free to explore the project and try out different models or enhancements!
