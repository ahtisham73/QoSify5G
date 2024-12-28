## 🌐📡QoSify5G: Resource Allocation Prediction & QoS Optimization in 5G Networks
---

# Table of Contents

1. [📚 Introduction](#introduction)
2. [🧑‍💻 Methodology](#methodology)
   - [Data Preprocessing](#data-preparation)
   - [Feature Engineering](#feature-engineering)
   - [Data Analysis & Visualizatio](#data-analysis)
   - [Prediction Models](#prediction-models)
3. [🔍 Findings](#findings)
4. [📈 Actionable Insights](#actionable-insights)
5. [🏁 Conclusion](#conclusion)

---

### 📚 [Introduction](#introduction)
This project focuses on analyzing, predicting, and optimizing resource allocation in 5G networks to enhance Quality of Service (QoS) for diverse application types. The study combines data preprocessing, feature engineering, and statistical analysis to understand how variables like `Application_Type`, `Signal_Strength`, and `Latency` impact network performance. Advanced machine learning models, including SVR, Gradient Boosting, and Random Forest, are employed to predict `Resource_Allocation` accurately. Insights from this analysis aim to support dynamic resource allocation strategies, improve bandwidth utilization, and ensure consistent QoS across varied use cases in 5G networks.

---

### 🧑‍💻 [Methodology](#methodology)
- **Data Preparation**: Conducted preprocessing, feature scaling, and engineering. Standardized variables for modeling and handled infinite/NaN values.
- **Data Analysis**: Applied ANOVA to study the impact of Application_Type on Resource_Allocation. Visualized relationships between network metrics using line plots and boxplots.
- **Prediction Models**: Built and tuned 4 machine learning models—SVR, Tuned SVR, Gradient Boosting, and Random Forest—achieving a best RMSE of 2.93 and R² of 0.9023 with the Tuned Random Forest.

---

### 🔍 [Findings](#findings)
- **Application types** significantly influence Resource_Allocation, with variations observed in Latency and Signal_Strength.
- Models effectively predicted Resource_Allocation, validating the importance of features like Bandwidth_Utilization_Ratio and Effective_Bandwidth_Usage.

---

### 📈 [Actionable Insights](#actionable-insights)
- Develop QoS-optimized resource allocation policies based on application type.
- Prioritize real-time metrics like **Bandwidth_Utilization_Ratio** and **Latency** for monitoring and dynamic network adjustments.
- Leverage predictive models for future resource allocation to enhance user experience.

---

### 🏁 [Conclusion](#conclusion)
This work demonstrates the potential of machine learning for analyzing and optimizing resource allocation in 5G networks. Future efforts should focus on real-world testing of proposed strategies and integrating predictive models into live 5G systems.
