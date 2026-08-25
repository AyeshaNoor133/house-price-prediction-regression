# house-price-prediction-regression
# 🏡 House Price Prediction using Linear Regression

##  Task Overview
This project builds a Multiple Linear Regression model to predict California home values based on demographic and structural housing features.

---

## 🛠️ Features Selected
1. **`MedInc`**: Median income in the block group
2. **`AveRooms`**: Average number of rooms per household
3. **`HouseAge`**: Median house age
4. **`AveOccup`**: Average number of household occupants

---

##  Performance Metrics

| Metric | Score | Explanation |
| :--- | :---: | :--- |
| **RMSE** | **~$73,800** | On average, predictions deviate by ~$73.8k from actual market values. |
| **$R^2$ Score** | **0.5120** | The model explains **51.2%** of the variance in housing prices. |

---

## Plain English $R^2$ Score Explanation
The $R^2$ score measures how well our model captures real-world price changes compared to just guessing the average house price. An $R^2$ score of **0.51** means our model's selected features (like local median income and household size) explain over half of the price differences between houses. The remaining variation is influenced by unmeasured factors like exact neighborhood quality, crime rates, or property upgrades.
