# 🌿💨 Greenhouse Gas Emission Prediction (GHG) – U.S. Industries & Commodities

This project 📊 focuses on analyzing and predicting greenhouse gas (GHG) emissions 💨 from various U.S. industries 🏭 and commodities 📦 using an official dataset from [Data.gov](https://www.data.gov/).

---

## 🎯 Project Goal

📌 To build predictive machine learning models that estimate greenhouse gas emissions (in kg CO₂e) based on supply chain data across industries and commodities in the United States 🇺🇸.

---

## 📂 Dataset Overview

📚 **Source**: [Supply Chain Greenhouse Gas Emission Factors – Data.gov](https://www.data.gov/)

This dataset provides supply chain emission factors linked to a wide range of U.S. industries and commodities.

### 🔑 Key Columns:

- 🏷️ **Code**: Industry classification code  
- 🏭 **Industry_Name**: Name of the industry  
- 📦 **Commodity**: Specific item or commodity name  
- 🌫️ **GHG_Emissions_kgCO2e**: GHG emissions per unit (kg CO₂ equivalent)  
- 📏 **Units**: Measurement units (e.g., kg/2018 USD, purchaser price)

---

## 🧹 Data Preprocessing

✨ **Steps involved**:

- 🧼 Handling missing/null values  
- ⚖️ Unit standardization  
- 🔠 Encoding categorical features  
- 📊 Scaling and normalizing numerical features  
- 🕵️‍♂️ Exploratory Data Analysis (EDA)

---

## 🤖 Model Building & Evaluation

We use machine learning models 🧠 to predict GHG emissions per commodity/industry.

### 🛠️ Models Used:
- 📐 Linear Regression  
- 🌲 Random Forest Regressor

### 📏 Evaluation Metrics:
- 🧮 **RMSE** – Root Mean Squared Error  
- 📉 **MAE** – Mean Absolute Error  
- 📈 **R² Score** – Model Accuracy (coefficient of determination)

---

## 🔄 Project Workflow

1. 📥 Import required libraries  
2. 📂 Load the dataset  
3. 🔍 Data preprocessing (EDA, cleaning, encoding)  
4. 🏋️‍♀️ Train regression models  
5. 🎯 Predict and evaluate  
6. 🎛️ Hyperparameter tuning  
7. 🥇 Comparative analysis & model selection

---

## 📊 Visual Insights

- 📌 Emission distribution by industry  
- 🔥 Correlation heatmaps  
- 🎯 Actual vs Predicted GHG plots  
- 🧪 Model performance comparison charts

---

## 🔗 Live Access

- 📘 [Open Colab Notebook](https://colab.research.google.com/drive/1NYih5AKu-9zRscyCrxmMEP3kIu7zlvu6?usp=sharing)  
- 📁 [Dataset & Model Files (Google Drive)](https://docs.google.com/spreadsheets/d/1TacGguugSdkJzf5duaqbJrSTNR91Di2s/edit?usp=drive_link&ouid=112898459691806049198&rtpof=true&sd=true)

> 📝 Replace the above URLs with your actual links.

---

## 🧰 Tools & Technologies

- 🐍 Python  
- 🐼 Pandas  
- 📊 Scikit-learn  
- 📈 Matplotlib & Seaborn  
- ☁️ Google Colab

---

## 🚀 Future Enhancements

- ⚡ Add more ML models (XGBoost, LSTM)  
- 🌐 Integrate real-time emissions data using APIs  
- 🧑‍💻 Build a web interface using Streamlit or Flask  
- 🌍 Extend to international data sources

---

## 🤝 Contributing

🙌 Contributions are welcome! Fork the repo, make changes, and submit a pull request 🚀

---

## 📄 License

📝 This project is open-source and licensed under the [MIT License](LICENSE)

---

