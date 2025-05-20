# Triggo.ai Technical Test 

![Status Badge](https://img.shields.io/static/v1?label=STATUS&message=INCOMPLETE&color=FFCC00)

## 🎯 Objectives
This repository contains notebooks and files used in a data analysis project focused on preparing, exploring and extracting business insights from a database obtained via the Kaggle API.

The guidelines for the technical test can be found [here](https://github.com/Triggo-ai4/desafio-data-engineer).

## 🎲 Database
To access the data, you need to set up access to the Kaggle API:

1. Go to your Kaggle profile > “Account” > “API” section > click on “Create New API Token”.

2. A file called kaggle.json will be downloaded automatically.

3. Save this file in a secure folder on your Google Drive.

4. At the beginning of the `triggo_ai_prep.ipynb` notebook, update the path with the correct location of your token.

For more details, see the official [Kaggle API documentation](https://www.kaggle.com/docs/api).

## 1. Data preparation

The steps of cleaning and transforming the datasets are described in this [Google Sheets](https://docs.google.com/spreadsheets/d/1nzsBwRFv1RVa1IVG4PNW-NKl76sO0iWDE-9pjh4RCOA/edit?usp=sharing) and were carried out in this notebook: `triggo_ai_prep.ipynb`.
At the end of the notebook, all the CSVs were integrated into a single file called `full_df.csv`.

## 2. Exploratory data 

The exploratory analysis was conducted in the `triggo_ai_eda.ipynb` notebook, with the aim of understanding the main characteristics of the data set and answering the questions requested.

## 3. Solving business problems

### a) What is the volume of orders per month? Are there seasonal sales?

### b) What is the distribution of order delivery times?

### c) What is the relationship between freight costs and delivery distance?

### d) What are the best-selling product categories in terms of turnover?

### e) Which Brazilian states have the highest average order value?

## 🛠️ Technologies used

![Python](https://img.shields.io/badge/-Python-blue?style=flat&logo=python&logoColor=yellow)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas&logoColor=150458)
![Google Colab](https://img.shields.io/badge/Colab-Notebook-%F9AB00?style=flat&logo=Google-Colab&color=F9AB00)
![Draw.io](https://img.shields.io/badge/Draw.io-Diagram-f08705?style=flat&logo=diagramsdotnet&logoColor=f08705)

## 👩🏻‍💻 Author

[![Linkedin Badge](https://img.shields.io/badge/-Patrícia-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/pathilink/)](https://www.linkedin.com/in/pathilink/)

## 🔓 License

[![License: MIT](https://img.shields.io/badge/License-MIT-750014.svg)](https://opensource.org/licenses/MIT)
