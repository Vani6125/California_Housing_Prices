# California_Housing_Prices

## 🏠 California Housing Price Prediction

This project aims to predict housing prices in California using various features like median income, number of rooms, location, and more. It follows a complete data science pipeline from data cleaning to model evaluation.

---

### 📌 Project Overview

* **Goal**: Predict median house values in California districts.
* **Dataset**:From Kaggle.
* **Tech Stack**: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Jupyter Notebook.

---

### 📊 Key Steps

1. **Data Preprocessing**

   * Handled missing values.
   * Applied log transformations to skewed features.
   * Engineered new features like:

     * `bedroom_ratio` = total bedrooms / total rooms
     * `rooms_per_household`

2. **Exploratory Data Analysis (EDA)**

   * Visualized distributions and correlations using Seaborn and Matplotlib.
   * Identified key features affecting house prices (e.g., median income, location).

3. **Model Building**

   * Built a Linear Regression model using Scikit-learn.
   * Evaluated performance using metrics like RMSE and R².

4. **Insights**

   * Median income was the most significant predictor of housing prices.
   * Engineered features improved model accuracy slightly.

---

### 📁 Files

| File                                  | Description                                        |
| ------------------------------------- | -------------------------------------------------- |
| `California_Housing_Prediction.ipynb` | Main Jupyter notebook containing code and analysis |
| `README.md`                           | Project overview and documentation                 |

---

### 🚀 Future Improvements

* Try advanced models like Random Forest, XGBoost.
* Hyperparameter tuning.
* Deploy the model as a simple web app (e.g., using Streamlit or Flask).
* Add interactive visualizations with Plotly.

---

### 🙋‍♀️ Author

**Manukonda Vani**
B.Tech student specializing in Artificial Intelligence and Machine Learning
