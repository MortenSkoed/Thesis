_This repository shows code made for Thesis handed in by Jens & Morten at Aarhus BBS 2024, Cand.merc FIB._

All different python scripts contains comments so the individual scripts can be understood. If you want to recreate scripts, you need to manually changes uploads as well as savining files produced from scripts, as the repository was made in Google Colab. 

# **Folders**

The repository is split into 3 different folders. We will describe functionalities of each folder subsequently. 

### 1. Data ###

The folder is split into two subfolders:
- Files
  - Contains input data used in the "Preprocessing" subfolder. Data contained in here is:
    - Macroeconomic data from FRED-MD
    - Freddie Mac HPI data
    - Michigan Survey sentiment data
    - Region split across US states indicator
- Preprocessing
  - Contains two python scripts
    - "Cleaned_Price":
      - In here the HPI data is converted from the CSV to dataframes so it can be used adequately in the other scripts.
    - "Merged_of_CleanPrices_&_Features":
      - Preprocessing of all data from the "Files" subfolder.  

### 2. Models ###
This folder contains both all alternative models and the AR(1) benchmark. More specifically:
  - AR(1)
  - AR(Optimal)
  - ARIMA
  - Random Forest
  - XGBoost

### 3. Model Performance ###
This folder contains model performances from the "Models" outputs. More specifically:
  - Performance over time
  - Performance Ratios
  - Performance Ratios excl. crisis periods
  - Statistical testing
