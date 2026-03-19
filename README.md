# Adult Income Prediction (Classification Comparison)

This project focuses on predicting whether an individual's annual income exceeds $50,000 based on various census and demographic data. It features an end-to-end machine learning workflow, comparing the performance of three different classification algorithms: **Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machines (SVM)**.

## 📊 Dataset Information

The project utilizes the "Adult Income" dataset. It includes several socio-economic features used to determine the income level:

* **Demographics**: Includes features such as age, gender, and race.

* **Employment**: Covers work class, occupation, and weekly working hours.

* **Education**: Includes education level and numerical years of schooling.

* **Target Variable**: `income` (classified as `>50K` or `<=50K`).

## 🛠️ Project Workflow

1. **Exploratory Data Analysis (EDA)**: Identification of missing values, analysis of data distributions, and correlation studies.

2. **Data Preprocessing**: 

    * Handling missing data and cleaning the dataset.
    
    * Encoding categorical variables into numerical format for model compatibility.

     * Feature scaling using `StandardScaler` to normalize data, which is essential for distance-based models like KNN and SVM.

4. **Model Selection & Training**: Implementation and training of Logistic Regression, K-Nearest Neighbors, and Support Vector Machines.

5. **Model Evaluation**: Assessment of performance using metrics such as Accuracy, Confusion Matrix, and Classification Reports.

## 🚀 Key Technologies

* **Python**: Main programming language.

* **Pandas & NumPy**: Used for data manipulation and numerical analysis.

* **Matplotlib & Seaborn**: Employed for data visualization and plotting.

* **Scikit-Learn**: The core library for machine learning modeling, scaling, and evaluation.

## 📁 Repository Structure

* `Adult Income prediction(Log_Reg - KNN - SVM).ipynb`: The complete Jupyter Notebook containing the full code, analysis, and visualizations.

* `adult.csv`: The raw dataset used for training and testing the models.

* `README.md`: Project documentation and summary.

## 📈 Results Summary

The project provides a comparative analysis to identify which model performs best on the provided
