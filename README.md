# 🩺 Breast Cancer Survival Analysis & Prediction  

## 📌 Project Overview  
Breast cancer is one of the most prevalent cancers globally, and predicting patient survival is crucial for better treatment planning. This project leverages **machine learning** and the **METABRIC (Molecular Taxonomy of Breast Cancer International Consortium) dataset** to analyze key clinical features and predict patient survival probabilities. The model provides **data-driven insights** that can assist oncologists in making informed treatment decisions.  

## 🎯 Objectives  
✔️ Perform **Exploratory Data Analysis (EDA)** to identify survival trends and key factors.  
✔️ Engineer and preprocess features to improve model accuracy.  
✔️ Develop multiple **machine learning models** (**Logistic Regression, Random Forest, XGBoost**) for prediction.  
✔️ Evaluate models using **performance metrics** like accuracy, precision, recall, and AUC-ROC.  
✔️ Build an **interactive Power BI dashboard** to visualize survival patterns.  
✔️ Deploy a **Streamlit web application** for real-time predictions.  

---  

## 📂 Dataset Information  
The **METABRIC dataset** contains clinical and genomic data of breast cancer patients.  

### 🔹 Key Features Used:  
- **Clinical Attributes:** Age, tumor size, lymph node status, tumor stage, subtype.  
- **Genomic Factors:** Mutations in specific genes (e.g., TP53, PIK3CA).  
- **Target Variable:** **Survival Status** (Survived/Deceased).  

### 🔹 Data Preprocessing Steps:  
1. **Handling Missing Values:** Imputation for missing clinical/genomic data.  
2. **Feature Selection:** Selecting impactful features for better model performance.  
3. **Encoding Categorical Variables:** Converting categorical features into numerical format.  
4. **Scaling & Normalization:** Standardizing continuous variables to optimize model training.  

---  

## 🛠 Tech Stack & Tools  
| Category              | Tools Used |
|----------------------|------------|
| **Programming**      | Python, SQL |
| **ML Libraries**     | Scikit-Learn, XGBoost, Pandas, NumPy |
| **Data Visualization** | Power BI, Matplotlib, Seaborn |
| **Deployment**       | Streamlit, Flask |
| **Cloud & Storage**  | IBM Cloud, Google Drive |

---  

## 🤖 Machine Learning Models  
- **Logistic Regression:** A simple yet effective baseline model.  
- **Random Forest:** An ensemble learning model that enhances prediction accuracy.  
- **XGBoost:** A powerful gradient boosting model that optimizes performance.  

### 📊 Model Evaluation Metrics:  
✔️ **Accuracy:** Measures the overall correctness of predictions.  
✔️ **Precision & Recall:** Evaluates false positives and false negatives.  
✔️ **F1-Score:** Balances precision and recall.  
✔️ **AUC-ROC Curve:** Measures model’s ability to distinguish between classes.  

---  

## 📊 Power BI Dashboard  
📌 **Key Insights Visualized:**  
- **Survival Rates by Age & Tumor Stage**  
- **Impact of Gene Mutations on Survival**  
- **Comparative Analysis of Treatment Outcomes**  

🔗 *[Dashboard Link]* _(To be added upon deployment)_  

---  

## 🚀 Deployment & Usage  
### 🔹 **1. Local Deployment (Streamlit)**  
Run the following command to launch the Streamlit app locally:  
```bash
streamlit run app.py
