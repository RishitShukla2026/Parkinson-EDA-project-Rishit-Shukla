# Parkinson's Disease Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing the Parkinson's Disease dataset using Python. It explores different voice measurement parameters and uses data analysis techniques to understand patterns in the dataset.

The project uses Python libraries such as Pandas, NumPy, and Matplotlib to perform data analysis, calculate statistical values, filter records, and visualize results through graphs.

## 🎯 Objectives

- Load and explore the Parkinson's Disease dataset.
- Display the first and last five records.
- Understand dataset structure and information.
- Calculate statistical measurements such as mean, median, minimum, and maximum.
- Count records according to their status.
- Compare average measurements between different status groups.
- Identify the top 10 highest MDVP:Fo(Hz) values.
- Filter records based on specific conditions.
- Generate graphs for better visualization.

## 🛠️ Technologies Used

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical calculations.
- **Matplotlib** – Data visualization.
- **Google Colab / Jupyter Notebook** – Development environment.

## 📂 Dataset Information

The project uses the `parkinsons.data` dataset.

Dataset details:

- Total Records: 195
- Total Columns: 24
- Numerical Columns: 23
- Text Columns: 1
- Missing Values: 0
- Duplicate Records: 0

The dataset contains voice-related measurements, including:

- MDVP:Fo(Hz)
- MDVP:Fhi(Hz)
- MDVP:Flo(Hz)
- MDVP:Jitter(%)
- MDVP:Shimmer
- NHR
- HNR
- RPDE
- DFA
- PPE

The `status` column represents the dataset's classification label.

## 📊 Analysis Performed

The following operations are performed in the project:

1. Loading the dataset using Pandas.
2. Displaying the first five and last five rows.
3. Checking dataset shape and information.
4. Generating summary statistics.
5. Checking missing values and duplicate records.
6. Counting records according to status.
7. Calculating mean, median, minimum, and maximum values.
8. Performing NumPy array calculations.
9. Comparing average measurements by status.
10. Finding the top 10 highest MDVP:Fo(Hz) values.
11. Filtering records where MDVP:Fo(Hz) is greater than 200 Hz.

## 📈 Visualizations

Two graphs are generated using Matplotlib:

**1. Record Count by Status**

A bar chart showing the number of records belonging to each status category.

**2. Distribution of MDVP:Fo(Hz)**

A histogram showing the distribution of fundamental voice frequency measurements across the dataset.

## 📋 Key Results

- Total records analyzed: 195.
- Status 1 records: 147.
- Status 0 records: 48.
- Missing values: 0.
- Duplicate records: 0.
- Average MDVP:Fo(Hz): 154.23 Hz.
- Median MDVP:Fo(Hz): 148.79 Hz.
- Minimum MDVP:Fo(Hz): 88.33 Hz.
- Maximum MDVP:Fo(Hz): 260.11 Hz.
- Records with MDVP:Fo(Hz) greater than 200 Hz: 34.

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Make sure Python is installed, or open Google Colab.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib
```

4. Upload the `parkinsons.data` dataset.
5. Open `ParkinsonsProjectRishit.ipynb`.
6. Update the dataset file path if necessary.
7. Run all notebook cells to see the analysis, outputs, and graphs.

## 📁 Project Structure

```text
Parkinsons-Disease-Analysis/
│
├── ParkinsonsProjectRishit.ipynb
├── parkinsons.data
└── README.md
```

## ⚠️ Disclaimer

This project is intended for educational purposes and demonstrates data analysis using Python. It is not a medical diagnostic system and should not be used to diagnose or make medical decisions.

## 🏁 Conclusion

This project demonstrates how Python can be used to explore, analyze, and visualize healthcare-related datasets. By using Pandas, NumPy, and Matplotlib, different statistical measurements and patterns can be studied effectively.

The project also provides practical experience in data handling, filtering, statistical analysis, and graphical representation.

---

**Project Name:** Parkinson's Disease Data Analysis  
**Created By:** Rishit Shukla
**admission number** 2026B01010331
**Language:** Python
