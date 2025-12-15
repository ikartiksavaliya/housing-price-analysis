# 🏠 Housing Price Analysis

A machine learning pipeline designed to analyze housing data and predict property prices using regression techniques. This project identifies key drivers of real estate value, such as median income, location, and household density.

## 📂 Repository Structure

| File / Folder | Description |
| :--- | :--- |
| `housing_price_analysis.ipynb` | The main Jupyter Notebook containing the data pipeline, feature engineering, and model training logic. |
| `datasets/` | Directory containing the housing dataset used for training and testing. |
| `requirements.txt` | List of Python dependencies required to run the project. |

## 🚀 Project Overview

The goal of this analysis is to build a predictive model for housing prices and detect market anomalies. The workflow includes:

1.  **Data Ingestion & Cleaning:** Handling missing values and outliers.
2.  **Exploratory Data Analysis (EDA):** Visualizing correlations between features (e.g., income vs. house value).
3.  **Feature Engineering:** Creating new attributes to improve model performance.
4.  **Model Training:** Implementing Linear Regression and Random Forest Regressors.
5.  **Evaluation:** Using RMSE (Root Mean Squared Error) to measure accuracy.

## 🛠️ Tech Stack

* **Python 3.x**
* **Pandas & NumPy** (Data manipulation)
* **Matplotlib & Seaborn** (Visualization)
* **Scikit-Learn** (Machine Learning models)

## ⚙️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ikartiksavaliya/housing-price-analysis.git](https://github.com/ikartiksavaliya/housing-price-analysis.git)
    cd housing-price-analysis
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch the Analysis:**
    ```bash
    jupyter notebook housing_price_analysis.ipynb
    ```

## 📊 Key Insights

* **Median Income** is the strongest predictor of housing prices.
* **Location** (latitude/longitude) and proximity to the ocean significantly impact value.
* **Population Density** plays a complex role in pricing dynamics compared to total room count.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
