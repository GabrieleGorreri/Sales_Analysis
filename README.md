# 📱Consumer Electronics Sales Analysis

## Introduction
Real data analysis project with Python Pandas about sales electronics 📈 

## 📒 Index
- [About](#beginner-about)
- [File Structure](#file_folder-file-structure)
- [Task #1](#wrench-task-#1)
- [Task #2](#wrench-task-#2)
- [Resources](#💾-resources)
- [Credit](#💡-credit)


##  📄 About
This data analysis projects aims to analyze and answer business questions about 12 months worth of sales data, about consumer electronics. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

### Tools
- Python: Pandas, Plotly

##  📁 File Structure
Here below is the folder structure containing the files used in the analysis, and the python notebook:

```
Sales_Analysis
├── Sales_Data
│   ├── Sales_December_2019.csv
│   ├── Sales_October_2019.csv
│   ├── Sales_June_2019.csv
│   ├── Sales_November_2019.csv
│   ├── Sales_July_2019.csv
│   ├── Sales_February_2019.csv
│   ├── Sales_March_2019.csv
│   ├── Sales_September_2019.csv
│   ├── Sales_January_2019.csv
│   ├── Sales_April_2019.csv
│   ├── Sales_August_2019.csv
├── Sales_Analysis.ipynb
├── Graphs
└── README.md
```

Those are the varaibles for each .csv file

| ORDER ID | PRODUCT | QUANTITY ORDERED | PRICE EACH | ORDER DATE | PURCHASE ADDRESS 
|----|------------|-------|-------|-------|-------|


##  🔧 Task #1
Cleaning our data. Tasks during this section include:

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

##  🔧 Task #2
Data exploration section. In this section we explore 5 high level business questions related to our data:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

##  💾 Resources
[Github Repository](https://github.com/KeithGalli/Pandas-Data-Science-Tasks) 

[YouTube Video](https://www.youtube.com/watch?v=eMOA1pPVUc4&t=802s)

## 💡 Credit
[Keith Galli](https://github.com/KeithGalli)


