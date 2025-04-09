# Liver-Cancer-Bangladesh 

# Lung Cancer Survival Prediction Dataset (This dataset is validated form sir salimullah medical college mitford hospital,Dhaka, Bangladesh)

## 📌 Overview
This dataset has been carefully synthesized to support research in lung cancer survival prediction, enabling the development of models that estimate:

- Whether a patient is likely to survive at least one year post-diagnosis (Binary Classification).
- The probability of survival based on clinical and lifestyle factors (Regression Analysis).

The dataset is designed for machine learning and deep learning applications in medical AI, oncology research, and predictive healthcare.

## 📜 Dataset Generation Process
The dataset was generated using a combination of real-world epidemiological insights, medical literature, and statistical modeling. The feature distributions and relationships have been carefully modeled to reflect real-world clinical scenarios, ensuring biomedical validity.

## 📖 Medical References & Sources
The dataset structure is based on well-established lung cancer risk factors and survival indicators documented in leading medical research and clinical guidelines:

- World Health Organization (WHO) Reports on lung cancer epidemiology.
- National Cancer Institute (NCI) & American Cancer Society (ACS) guidelines on lung cancer risk factors and treatment outcomes.
- The IASLC Lung Cancer Staging Project (8th Edition): Standard reference for lung cancer staging.
- Harrison’s Principles of Internal Medicine (20th Edition): Provides an in-depth review of lung cancer diagnosis and treatment.
- Lung Cancer: Principles and Practice (2022, Oxford University Press): Clinical insights into lung cancer detection, treatment, and survival factors.

## 🔬 Features of the Dataset
Each record in the dataset represents an individual’s clinical condition, lifestyle risk factors, and survival outcome. The dataset includes the following features:

### 1️⃣ Patient Demographics
- **Age** → A key risk factor for lung cancer progression and survival.
- **Gender** → Male and female lung cancer survival rates can differ.
- **Residence** → Urban vs. Rural (impact of environmental factors).

### 2️⃣ Risk Factors & Lifestyle Indicators
These factors have been linked to lung cancer risk in epidemiological studies:
- **Smoking Status** → (Current Smoker, Former Smoker, Never Smoked).
- **Air Pollution Exposure** → (Low, Moderate, High).
- **Biomass Fuel Use** → (Yes/No) – Associated with household air pollution.
- **Factory Exposure** → (Yes/No) – Industrial exposure increases lung cancer risk.
- **Family History** → (Yes/No) – Genetic predisposition to lung cancer.
- **Diet Habit** → (Vegetarian, Non-Vegetarian, Mixed) – Nutritional impact on cancer progression.

### 3️⃣ Symptoms (Primary Predictors)
These are key clinical indicators associated with lung cancer detection and severity:
- **Hemoptysis** (Coughing Blood)
- **Chest Pain**
- **Fatigue & Weakness**
- **Chronic Cough**
- **Unexplained Weight Loss**

### 4️⃣ Tumor Characteristics & Clinical Features
- **Tumor Size (mm)** → The size of the detected tumor.
- **Histology Type** → (Adenocarcinoma, Squamous Cell Carcinoma, Small Cell Carcinoma).
- **Cancer Stage** → (Stage I to Stage IV).

### 5️⃣ Treatment & Healthcare Facility
- **Treatment Received** → (Surgery, Chemotherapy, Radiation, Targeted Therapy).
- **Hospital Type** → (Private, Government, Medical College).

### 6️⃣ Target Variables (Predicted Outcomes)
- **Survival (Binary)** → 1 (Yes) if the patient survives at least 1 year, 0 (No) otherwise.
- **Survival Probability (%)** (Can be derived) → Estimated probability of survival within one year.

## ⚡ Why This Dataset is Valuable?
- **✅ Balanced Data Distribution**: Designed to ensure a representative distribution of lung cancer survival cases, preventing model bias and improving generalization in predictive models.
- **✅ Medically-Inspired Feature Engineering**: Features are derived from real-world lung cancer risk factors, validated through medical literature. Incorporates both lifestyle and clinical indicators to enhance predictive accuracy. *(No real person data is used, just simulated biomedical environment)*
- **✅ Diverse Risk Factors Considered**: Smoking, air pollution, and genetic history as primary lung cancer contributors. Symptom severity and tumor histology influence survival rates.
- **✅ Scalability & ML Suitability**: Ideal for classification and regression tasks in machine learning. Can be used with deep learning (TensorFlow, PyTorch), ML models (XGBoost, Random Forest, SVM), and explainable AI techniques like SHAP and LIME.

## 📂 Dataset Usage & Applications
This dataset is highly useful for multiple healthcare AI applications, including:

- 🩺 **Predictive Analytics** → Early detection of high-risk lung cancer patients.
- 🤖 **Healthcare Chatbots** → AI-powered risk assessment tools.
