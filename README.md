# ⚡ EV Adoption Prediction & Forecasting (Shell Capstone)

![Project Status](https://img.shields.io/badge/status-completed-success.svg)
![Partner](https://img.shields.io/badge/Partner-Shell%20%7C%20Edunet-yellow.svg)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/sklearn-Random%20Forest-orange?style=flat&logo=scikit-learn&logoColor=white)

## 📖 About

This repository contains the source code and datasets for the **Electric Vehicle (EV) Prediction Project**, developed as part of the specialized training program offered by **Shell** in collaboration with **Edunet Foundation**.

The project aims to analyze historical EV population data to forecast future adoption rates and assist in strategic decision-making for EV infrastructure deployment.

### 🔍 Key Objectives
-   **Data Analysis:** Cleaning and exploring real-world EV population data by county.
-   **Modeling:** Building Machine Learning models (specifically **Random Forest**) to predict EV adoption trends.
-   **Forecasting:** Generating future insights to help stakeholders prepare for the energy transition.

## 📂 Project Structure

| File/Folder | Description |
| :--- | :--- |
| `EV_Adoption_Forecasting.ipynb` | Main notebook for time-series forecasting of EV growth. |
| `EV_Pridiction_model.ipynb` | Notebook focusing on predictive modeling (Regression/Classification). |
| `Electric_Vehicle...By_County.csv` | Raw input dataset containing EV stats by region. |
| `preprocessed_ev_data.csv` | Cleaned dataset ready for model training. |
| `forecasting_ev_model.pkl` | The trained ML model saved for future use. |
| `RF_Tree.png` | Visualization of a single tree from the Random Forest model. |
| `Practice File...Shell.ipynb` | Week 1 exploratory exercises and verified practice code. |

## 🛠️ Tech Stack

-   **Language:** Python
-   **IDE:** Jupyter Notebook / Google Colab
-   **Libraries:** -   `pandas` & `numpy` (Data Manipulation)
    -   `scikit-learn` (Machine Learning: Random Forest)
    -   `matplotlib` & `seaborn` (Visualization)

## 🚀 Getting Started

Follow these steps to replicate the analysis on your local machine.

### Prerequisites

Ensure you have Python installed along with the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
