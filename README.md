# SemProject_MLEngine: EV Battery Health & Failure Prediction System

## Project Title **EV Battery Health & Failure Prediction System**

## Overview
This project focuses on developing a machine learning-powered system to predict Electric Vehicle (EV) battery health degradation and potential failure risks. The ultimate goal is to create a robust predictive model that can power a mobile application, providing EV owners with real-time insights into their battery's condition and personalized maintenance recommendations to extend battery life and prevent unexpected failures.

## Datasets Considered
For this project, two candidate datasets were considered, both containing synthetic, physics-informed data related to EV battery performance and health:

1.  **EV Battery Failure Prediction Dataset (200K records)**: A larger dataset offering extensive data points for potential in-depth analysis.
    *   Source: [https://www.kaggle.com/datasets/sarveshchhetri/ev-battery-failure-prediction-dataset-200k]
2.  **EV Battery Health Prediction Dataset (20K records)**: A more compact dataset, suitable for focused exploration and model development.
    *   Source: [https://www.kaggle.com/datasets/srisyra02/ev-battery-health-prediction-dataset-20k]

## Selected Dataset
We have selected the **EV Battery Health Prediction Dataset (20K records)** for our project. This dataset offers a right-sized collection of data that is manageable for a university class project, allowing for thorough exploration, feature engineering, and model training without encountering excessive computational runtimes or resource constraints.

## Target Variable(s)
Based on our dataset exploration, the following variables have been identified as primary candidates for the machine learning model's output:

*   `battery_failure`: A binary variable (0 or 1) indicating whether a battery has failed. This is suitable for **classification** tasks.
*   `predicted_remaining_life_cycles`: A continuous numerical variable estimating the remaining operational life cycles of the battery. This is suitable for **regression** tasks.

## Repository Structure
```
SemProject_MLEngine/
├── EVBatteryHealth_Exploration.ipynb  # Main Jupyter Notebook for data exploration, cleaning, and initial analysis
├── data/                             # Directory for raw and processed datasets
│   ├── ev battery_failure prediction Dataset(20K).csv
│   ├── ev_battery_failure_dataset.csv
│   └── data_dictionary.csv
├── README.md                         # Project README file
└── .gitignore                        # Git ignore file
```

## How to Run
To run the data exploration notebook, `EVBatteryHealth_Exploration.ipynb`, in Google Colab:

1.  Open Google Colab in your web browser.
2.  Go to `File > Upload notebook` and select `EVBatteryHealth_Exploration.ipynb` from this repository, or go to `File > Open notebook` and select it from your Google Drive if you have synced the repository.
3.  Ensure that the dataset files (`ev battery_failure prediction Dataset(20K).csv`, `ev_battery_failure_dataset.csv`, `data_dictionary.csv`) are correctly mounted in your Google Drive at `/content/drive/MyDrive/EV Battery Health/` and `/content/drive/MyDrive/EV Battery Health/EV Battery Health200K/` respectively, as referenced in the notebook.
4.  Run all cells in the notebook (`Runtime > Run all`) to reproduce the data exploration and analysis.

## Team Members
*   [Ryan Moturi-166096]
*   [Victor Musembi Nzai-166341]
*   [Sandra Cheruto-190381]
*   [Team Member 4 Name]

## Deliverables Progress
*   ✅ **Deliverable 1: Dataset Discovery & Exploration** - *Complete*
*   ⬜ **Deliverable 2: Model Selection & Implementation** - *Pending*
*   ⬜ **Deliverable 3: Presentation & Final Report** - *Pending*
