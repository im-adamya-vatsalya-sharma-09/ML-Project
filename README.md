# System Threat Forecaster

## 🚀 Overview

**System Threat Forecaster** is a machine learning project aimed at predicting potential system security threats and vulnerabilities. By analyzing telemetry data collected from system antivirus software, the project forecasts the likelihood of a system being infected by various malware families. This predictive capability assists in proactive threat management and enhances overall cybersecurity measures.

---

## ❓ Problem Statement

In the realm of cybersecurity, timely detection and prevention of threats are paramount. Traditional methods often react to threats post-occurrence, leading to potential system compromises. This project addresses the need for a predictive model that can analyze system telemetry data to forecast potential threats, enabling preemptive actions to safeguard systems.

---

## 🗂️ Dataset

The dataset used in this project includes telemetry data collected from Windows Defender antivirus software, which consists of:

- System specifications (e.g., OS version, RAM size)
- Antivirus software logs
- Historical threat detection records

This rich dataset provides the foundation for training machine learning models to predict system vulnerabilities effectively.

---

## 🧠 Methodology

The project follows a structured approach:

1. **Data Preprocessing**  
   - Cleaning and preparing the dataset  
   - Handling missing values  
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**  
   - Understanding data distributions  
   - Identifying patterns and correlations  
   - Visualizing relationships between features

3. **Feature Engineering**  
   - Creating new features  
   - Feature selection using importance metrics

4. **Model Selection**  
   - Evaluated multiple algorithms:  
     - XGBoost
     - SGD 
     - KNN 
     - Decision Tree

5. **Model Training and Evaluation**  
   - Assessed using accuracy, precision, recall, and F1-score

6. **Deployment Considerations**  
   - Model integration for real-time threat detection systems (suggested future work)

---

## 📈 Results

The machine learning models demonstrated high potential in threat forecasting:

- **Accuracy**: Up to 62% on test data which is very good in comparision to the other same problem statements.
- **Precision and Recall**: High values indicating strong detection with minimal false positives
- **Feature Importance**: Key features like `AVProductStatesIdentifier`, `IsProtected`, and `OsBuildLab` were critical in threat prediction

---

## 💻 Installation and Usage

To run this project locally:

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/im-adamya-vatsalya-sharma-09/ML-Project.git
