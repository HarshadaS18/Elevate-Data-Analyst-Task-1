 Task 1: Data Cleaning and Preprocessing - Netflix Dataset

📌 Objective
To clean and prepare a raw Netflix Movies and TV Shows dataset by handling missing values, standardizing text, correcting data types, and resolving anomalies (such as misplaced rating/duration fields)[cite: 1].

 🛠️ Tools Used
* **Python (Pandas, NumPy)**[cite: 1]
* **Jupyter Notebook**

🔍 Steps Performed & Summary of Changes
1. **Initial Inspection:** Checked dataset dimensions ($8807$ rows, $12$ columns), data types, and summary statistics.
2. **Missing Values:** Identified and handled null counts in critical columns (`director`, `cast`, `country`, `rating`) using appropriate placeholders/imputations[cite: 1].
3. **Duplicate Check:** Verified that zero duplicate rows existed using `.duplicated()`[cite: 1].
4. **Data Type Conversion:** Converted `date_added` into proper `datetime` objects[cite: 1].
5. **Data Quality Fixes:** Detected and investigated anomalies where duration values leaked into the `rating` column, ensuring data integrity for future analysis[cite: 1].
6. **Export:** Generated and saved the final cleaned dataset as `netflix_cleaned_dataset.csv`[cite: 1, 2].

📁 Repository Contents
* `netflix_data.csv` - Raw dataset
* `Netflix_Data_Cleaning.ipynb` - Jupyter notebook containing all Python cleaning code[cite: 2, 3]
* `netflix_cleaned_dataset.csv` - Final cleaned and processed dataset[cite: 1, 2]
