# 🧠 ML Business Intelligence – End-to-End Machine Learning Pipeline  

This project demonstrates an end-to-end **Machine Learning Business Intelligence solution** — covering data preprocessing, feature engineering, model training, and deployment on cloud platforms using Flask.  
It showcases practical skills in building scalable ML systems ready for production.

---

## 📅 Project Duration
**June 2024 – July 2024**  
Created and documented by **Ankit Kumar**  

---

## 📋 About the Project
The dataset used for this project contains **student performance metrics** in math, reading, and writing, based on several socioeconomic and educational factors such as gender, parental education, and access to preparatory courses.  

The goal is to predict **math scores** based on these features using multiple machine learning models.  
This regression-based ML pipeline implements end-to-end steps — from EDA to deployment — under a Business Intelligence workflow.

---

## 🎯 Objective
Build a complete **ML pipeline** capable of:
- Collecting, cleaning, and transforming raw data  
- Building predictive ML models  
- Deploying trained models to cloud platforms for real-world access  
- Demonstrating reproducibility and scalability through modular code  

---

## ⚙️ Machine Learning Algorithms Used
- Linear Regression  
- Lasso & Ridge Regression  
- K-Nearest Neighbors (KNN) Regressor  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor  
- CatBoost Regressor  
- AdaBoost Regressor  

After training, models were compared on performance metrics like **R² Score**, **RMSE**, and **MAE**.  
The top-performing model was selected for deployment.

---

## 🌐 Deployed Model
For demonstration, this project can be extended for deployment on:
- **AWS Elastic Beanstalk**
- **Microsoft Azure Web Apps**

*(Currently configured locally for testing.)*

You can explore this version and future deployments here:  
🔗 [**My GitHub Repository**](https://github.com/MAnkitkumar/ML_Business_Intelligence_Ankit)

---

## 🧩 Project Guidelines
1. Clean, modular code with comments and structure.
2. Separation of concerns — scripts for ingestion, transformation, training, and prediction.  
3. Deployment-ready pipeline architecture.  
4. Compatibility for AWS / Azure deployment.

---

## 🗺️ Project Roadmap
1. **EDA & Model Training (Notebook Phase)**  
   - Perform Exploratory Data Analysis (EDA).  
   - Train and tune models using Scikit-learn and XGBoost.  
   - Evaluate using cross-validation.  

2. **Error Handling & Logging**  
   - Implement custom exceptions for controlled error messages.  
   - Generate logs for pipeline monitoring.

3. **Data Ingestion & Transformation**  
   - Handle missing values and categorical encoding.  
   - Build preprocessing pipelines using `ColumnTransformer`.

4. **Model Training & Evaluation**  
   - Compare regression models and perform hyperparameter tuning.  
   - Save the trained model as a `.pkl` artifact.

5. **Flask Web Application**  
   - Build an input-based prediction UI.  
   - Load the trained model and preprocessor for real-time predictions.  

6. **Cloud Deployment**  
   - Configure AWS Elastic Beanstalk / Azure Web App pipeline.  
   - Enable Continuous Delivery from GitHub repository.  

---

## 📦 Dependencies
Install these dependencies before running the project:

```bash
pip install -r requirements.txt
