# 5243_project1-Team4
2025/2/14  Jinze Shi: I have done the outlier task and find the we don't have repeat data,I have update the data(cleaned_selected_features.csv) and code(Data_col_lastest_version.ipynb). Please use the use data and code to move on your work.


2025/2/13  Jinze  Shi:  I  have  upload  my  part  code(Data_col.ipynb)  and  the  csv  file(selected_features_with_names.csv),  which  you  can  use  directly.  !!!!!!!!Attention,when  you  use  use  the csv  data,  remember  that  the  feature(State)  should  be  the  object.  
Below  is  what  I  have  done
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


I completed a series of data processing, feature selection, and data cleaning tasks, including:

1. **Data Loading and Inspection**:
   - I loaded the *Communities and Crime* dataset from the UCI Machine Learning Repository.
   - I checked the data types (`df.dtypes`) to identify which columns were `float64`, `int64`, and `object`.
   - I counted the number of missing values in the dataset using `df.isnull().sum()`.

2. **Handling Missing Values**:
   - I applied **KNN imputation** to fill missing values for `feature_0` to `feature_5`.
   - I replaced missing values in the remaining columns with their respective **mean values**.

3. **Feature Selection**:
   - I used **OLS regression**, **Lasso regression**, **Elastic Net**, and **Stepwise Selection** to identify the most important features.
   - I counted how many times each feature was selected across different methods.
   - I finalized the **top 10 most important features** and created a new dataset containing only these features.

4. **Feature Naming**:
   - I retrieved the actual feature names from the UCI dataset documentation.
   - I mapped the most important features to their corresponding names, such as:
     - `feature_6` → **householdsize**
     - `feature_47` → **PersPerFam**
     - `feature_74` → **PctHousLess3BR**
     - `feature_53` → **NumIlleg**
     - `feature_0` → **state**
     - `feature_71` → **PersPerRentOccHous**
     - `feature_77` → **PctHousOwnOcc**
     - `feature_51` → **PctWorkMomYoungKids**
     - `feature_91` → **MedRentPctHousInc**
     - `feature_31` → **NumUnderPov**

5. **Final Data Output**:
   - I created a new CSV file (`selected_features_with_names.csv`) that contains only the **top 10 most important features**, with proper column names for clarity.

Through this process, I reduced the dataset from **127 features** to the **10 most relevant ones**, making it more suitable for further analysis or machine learning applications. 
