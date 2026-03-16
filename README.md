# AI Depression Relapse Prediction using Meta-Analysis and Machine Learning

## Project Overview

This project combines **systematic review methodology, meta-analysis, and machine learning** to predict the **risk of depression relapse**.

The study began with a **systematic literature search across multiple medical databases**, followed by screening and data extraction from randomized controlled trials. The extracted dataset was then used to build a **machine learning model that predicts relapse probability for new patients and identifies the most influential risk factors**.

The final model allows a user to input patient characteristics and receive:

• Predicted probability of depression relapse
• Key factors contributing to relapse risk

This project demonstrates the integration of **clinical research methods and artificial intelligence for mental health prediction**.

---

# Research Workflow

The project followed a structured research pipeline.

### 1. Data Collection

Articles were collected from multiple academic databases:

* Google Scholar
* PubMed
* ClinicalTrials.gov
* Cochrane Library

Total articles collected: **2097**

---

### 2. Duplicate Removal

Duplicates were removed using **Zotero reference manager**.

Remaining articles after deduplication:

**1700 studies**

---

### 3. Initial Screening

Initial screening was performed using **Rayyan AI**, based on titles and abstracts.

Articles selected after screening:

**67 studies**

---

### 4. Full-Text Review

Full article screening was conducted to determine eligibility based on study design and relevance.

Final studies included:

**10 randomized controlled trials**

---

### 5. Data Extraction

Data was extracted from the selected studies including:

* Age of participants
* Gender distribution
* Baseline depression scores (BDI, HRSD)
* Previous depressive episodes
* Medication status
* Number of therapy sessions
* Follow-up duration
* Relapse outcomes

This information was compiled into a structured dataset for further analysis.

---

# Machine Learning Pipeline

The extracted dataset was processed using a machine learning workflow.

### Data Processing

* Data cleaning
* Handling missing values
* Feature encoding
* Feature scaling

### Feature Engineering

Relevant clinical variables were prepared for machine learning models.

### Model Training

A **Random Forest model** was trained to predict depression relapse probability.

### Model Evaluation

Model performance was evaluated using standard machine learning metrics.

---

# Meta-Analysis and Visualization

Meta-analysis techniques were used to analyze relapse outcomes across the included studies.

Visualizations generated in this project include:

* Meta-analysis plots
* Feature importance analysis
* Relapse risk visualization
* Patient-level prediction examples

---

# AI Prediction Model

The final system allows prediction of relapse risk for a new patient.

### Input Variables

* Age
* Gender
* BDI Score
* HRSD Score
* Previous Depressive Episodes
* Medication Status
* Number of Therapy Sessions
* Follow-up Duration

### Output

The model provides:

1. **Predicted probability of depression relapse**
2. **Feature importance explanation showing which factors contributed most to the prediction**

Example Output:

```
Predicted relapse risk: 0.32

Top contributing factors:
1. Baseline BDI score
2. Previous depressive episodes
3. Follow-up duration
```

---

# Project Structure

```
AI_Depression_Relapse_Prediction
│
├── data
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks
│   ├── DataCleaning.ipynb
│   ├── FeatureEngineering.ipynb
│   └── ModelTraining.ipynb
│
├── models
│   └── random_forest_depression_model.pkl
│
├── figures
│   ├── meta_analysis_plot.png
│   └── feature_importance_plot.png
│
├── scripts
│   └── patient_prediction.py

```

---

# Technologies Used

Python was used for the entire analysis and machine learning workflow.

Libraries used include:

* pandas
* numpy
* scikit-learn
* xgboost
* matplotlib
* seaborn

The project was developed using **Google Colab and Jupyter Notebook**.

---

# Skills Demonstrated

This project demonstrates the following skills:

* Systematic review methodology
* Research article screening
* Clinical data extraction
* Meta-analysis concepts
* Machine learning model development
* Feature importance interpretation
* AI-based clinical risk prediction
* Data visualization
* GitHub project management

---

# Future Improvements

Possible future enhancements include:

* Larger clinical dataset integration
* Deep learning models for prediction
* Web application for patient risk assessment
* Integration with electronic health record data

---

# Author

**Ahmer Randhawa**

Artificial Intelligence Student
Machine Learning and Clinical Data Analysis
