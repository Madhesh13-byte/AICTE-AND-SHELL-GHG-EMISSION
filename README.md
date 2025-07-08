# 🌿 Greenhouse Gas Emission Prediction (GHG) – AICTE + Shell Internship

This project focuses on analyzing and predicting **greenhouse gas (GHG) emissions** from various U.S. industries and commodities using machine learning techniques. It was developed as part of the **AICTE + Shell internship program**.

## 🎯 Project Objective

To build and deploy a predictive machine learning model that estimates GHG emissions (in kg CO₂e) based on supply chain data of different industries and commodities.

---

## 📂 Dataset

- **Source**: [Supply Chain Greenhouse Gas Emission Factors – Data.gov](https://catalog.data.gov/)
- **Key Features**:
  - `Industry_Name` – Name of the industry
  - `Commodity` – Specific product or material
  - `GHG_Emissions_kgCO2e` – Emissions in kg CO₂ equivalent
  - `Units` – Measurement basis (e.g., kg/2018 USD, purchaser price)
  - `Source`, `Substance`, etc.

---

## 🔍 Methodology

1. **Data Collection** – Downloaded dataset from Data.gov
2. **Preprocessing** – Handled missing values, encoded categorical data, scaled numerical features
3. **EDA** – Visualized distributions, correlations, and emission trends
4. **Model Building** – Trained Linear Regression and Random Forest Regressor models
5. **Evaluation** – Used RMSE, MAE, and R² Score for comparison
6. **Hyperparameter Tuning** – Optimized model parameters using Grid Search
7. **Deployment** – Developed a **Streamlit** web app for real-time predictions

---

## 🛠️ Technologies Used

- **Python**  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Machine learning models  
- **Google Colab** – Model development  
- **Streamlit** – App deployment  

---

## 📸 Output Screenshots

- Emission distribution by industry
- Correlation heatmap
- Target variable distribution
- Streamlit prediction interface
- Actual vs. Predicted plots

*(See screenshots folder for more)*

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/GHG-Emission-Prediction.git
   cd GHG-Emission-Prediction
