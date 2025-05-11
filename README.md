# 🎮 Ice Store – Video Game Sales Analysis Project

This project is part of a data analysis task for Ice, a global online video game retailer. The goal is to identify patterns that determine whether a game is successful, using open data sources that include user and critic reviews, genres, platforms, ESRB ratings, and historical sales data. 

🕒 Context: We assume it is December 2016, and we are planning a marketing campaign for 2017. The data available goes up to 2016 and may be incomplete.

🧾 Project Description

The main objective is to:

Gain hands-on experience working with real-world datasets

Analyze global video game sales data

Identify trends, high-performing genres, and top platforms

Build user profiles by region

Perform hypothesis testing to validate assumptions about user ratings and sales

📁 Dataset Overview

The dataset contains the following columns:

Name: Game title

Platform: Console/platform (e.g., PS4, Xbox One)

Year_of_Release: Year the game was released

Genre: Game genre

NA_sales: Sales in North America (in millions USD)

EU_sales: Sales in Europe (in millions USD)

JP_sales: Sales in Japan (in millions USD)

Other_sales: Sales in other regions (in millions USD)

Critic_Score: Average score from critics (out of 100)

User_Score: Average user score (out of 10)

Rating: ESRB age classification (e.g., E, T, M)

📝 Note: The data for 2016 may be incomplete.

⚙️ Project Workflow

Step 1: Data Exploration
Load and explore the dataset

Understand the structure and quality of the data

Step 2: Data Preparation
Rename all column headers to lowercase

Convert data types as needed

Handle missing values and provide justifications

Explain any assumptions made (e.g., TBD entries)

Calculate total global sales per game and store in a new column

Step 3: Data Analysis
Number of game releases per year – assess the relevance of each time period

Analyze sales trends per platform

Identify top platforms by total sales

Track platform popularity over time

Select a relevant period for building a predictive model for 2017

Focus analysis on that period only

Identify leading, growing, and declining platforms

Create boxplots of global sales per platform

Study correlations between critic/user scores and sales

Compare performance of the same game across platforms

Explore genre distribution and profitability

Step 4: Regional User Profiles
For each region (North America, Europe, Japan):

Identify the top 5 platforms

Identify the top 5 genres

Examine whether ESRB ratings affect regional sales

Step 5: Hypothesis Testing
Test the following hypotheses:

Average user ratings for Xbox One and PC are the same

Average user ratings for Action and Sports games differ

Define null and alternative hypotheses

Choose an appropriate significance level (alpha)

Explain reasoning and interpret results

📊 Tools & Technologies
Python

pandas, numpy – data manipulation

matplotlib, seaborn – visualizations

scipy.stats – statistical testing

Jupyter Notebook – project implementation and presentation

🧠 Learning Goals
Practice cleaning and preparing real-world data

Gain insights through exploratory data analysis

Apply statistical methods to support data-driven decision-making

Communicate findings clearly and effectively

✅ Project Status
🟢 Completed – The analysis was conducted in Jupyter Notebook with code cells and well-structured markdown documentation. The insights gained can help inform 2017 marketing strategies based on historical trends in genres, platforms, and regional preferences.
