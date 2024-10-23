# 🌍 Climate Change: Preliminary Analysis and Prediction using Global Temperature Data

This repository is dedicated to the research paper **"Climate Change: Preliminary Analysis and Prediction using Global Temperature Data"**, published in the **American Journal of Electronics & Communication, Volume 3, Number 2 (2022)**. The paper aims to analyze historical temperature data, explore its correlation with climate factors such as CO2 emissions, and predict future temperature trends using machine learning techniques.

---

## 🔗 Research Paper Link

You can access the full paper here: https://www.researchgate.net/publication/364617105_Climate_Change_Preliminary_analysis_and_prediction_using_global_temperature_data

---

## 📜 Abstract

The effects of climate change are increasingly being felt worldwide, making it imperative to analyze and understand its underlying causes. This research utilizes global temperature data, provided by the United Nations, to examine trends and predict future temperature rises. The study cleans and restructures the raw data, then explores relationships between temperature changes and contributing factors such as rising **CO2 emissions**, **deforestation**, and the **Air Quality Index (AQI)**.

To predict future temperature trends, **linear regression** and **polynomial regression** models were trained on the cleaned data. The study forecasts temperature changes until 2059 using both **2-degree** and **5-degree** polynomial regression models, with predictions showing an alarming rise in global temperatures.

### Key Contributions:
- **Data Preprocessing**: The UN's global temperature dataset was cleaned and restructured for analysis.
- **Regression Models**: Both **linear** and **polynomial regression** models were used to train the data and predict future temperature changes.
- **Prediction**: The study predicts global temperature changes until 2059 using polynomial regression.
- **Factors Analysis**: Correlation between temperature rise and contributing factors like CO2 emissions, deforestation, and air quality was explored.

---

## 📊 Methodology and Models

The methodology is divided into several key components:

1. **Data Preprocessing**:
   - The UN-provided **Global Temperature Dataset** was cleaned and transformed for the analysis.
   - Data was normalized and standard deviation was applied to handle outliers.
   - Missing data points were handled using interpolation techniques.

2. **Model Training**:
   - **Linear Regression** was initially used to understand basic trends in temperature changes.
   - **Polynomial Regression** models (2-degree and 5-degree) were applied to capture more complex patterns.
   
3. **Temperature Prediction**:
   - Using polynomial regression, the model forecasts a continuous rise in global temperatures through 2059.
   - Predictive accuracy was validated using the **R-squared** value and error metrics.

4. **Correlation Analysis**:
   - Correlations between rising global temperatures and factors like CO2 emissions, loss of forest cover, and the Air Quality Index (AQI) were established.
   - The findings provide a deeper understanding of how these factors jointly contribute to global warming.

---

## 🛠️ Tools & Technologies

| Tool/Technology  | Description  |
| ---------------- | ------------ |
| ![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white) | For numerical data operations and array manipulation. |
| ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white) | Used for data cleaning, manipulation, and restructuring of the temperature dataset. |
| ![Scikit-learn](https://img.shields.io/badge/-Scikit_Learn-FF9900?logo=scikit-learn&logoColor=white) | The machine learning library for implementing linear and polynomial regression models. |
| ![Matplotlib](https://img.shields.io/badge/-Matplotlib-000000?logo=matplotlib&logoColor=white) | For visualizing the temperature trends and regression results. |
| **UN Global Temperature Data** | The dataset used for temperature change analysis and predictions. |

---

## 📈 Experimental Results

The study focused on evaluating the predictive power of **linear** and **polynomial regression** models. Some of the key results include:
- **Linear Regression** provided a simple yet clear representation of the rising temperature trends, with some limitations in capturing non-linear patterns.
- **2-degree Polynomial Regression** offered better accuracy for short-term predictions, capturing more nuanced patterns in temperature changes.
- **5-degree Polynomial Regression** demonstrated the ability to predict long-term temperature changes with higher precision, especially in the context of volatile climate patterns.
  
Predictions using these models suggest a continuous rise in temperatures up until 2059, raising concerns about the future impact of climate change.

---

## 🔮 Future Scope

- **Multi-Factor Climate Prediction**: Future work could explore incorporating more environmental factors (e.g., ocean currents, polar ice levels) to improve the prediction models.
- **Real-Time Climate Data**: Using real-time climate data along with machine learning algorithms to enhance the accuracy of predictions.
- **Advanced Machine Learning Models**: Explore the use of deep learning models such as LSTMs or GRUs for time-series climate predictions.
- **Policy Simulation**: Simulate the impact of potential climate policies on temperature predictions, helping policymakers design effective interventions.

---

## ✨ Contributors

- **Vandana Jagtap** – [MIT-WPU, Pune, India](mailto:vandana.jagtap@mitwpu.edu.in)
- **Yash Rathore** – [MIT-WPU, Pune, India](mailto:yashrathore02061999@gmail.com)
- **Sarthak Oke** – [MIT-WPU, Pune, India](mailto:sarthakoke@gmail.com)
- **Parth Gawande** – [MIT-WPU, Pune, India](mailto:parthgawande2000@gmail.com)
- **Pooshan Singh** – [MIT-WPU, Pune, India](mailto:pooshansingh@mitwpu.edu.in)


