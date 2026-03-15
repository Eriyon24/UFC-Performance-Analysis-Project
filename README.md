UFC Fighter Performance Analysis

Author: Eriyon Adams

Project Summary

This project analyzes UFC fight data to examine how fighter activity and damage taken may influence performance outcomes. Using Python and Power BI, the analysis explores the relationship between time between fights (rest periods), damage absorbed, and fight results.

The goal of the project is to demonstrate practical data analysis, feature engineering, and visualization skills using real-world sports data.

Key Questions

Does the amount of time between fights affect a fighter’s chance of winning?

Do fighters who absorb more damage tend to lose more often?

How do different fight outcomes (KO/TKO, submission, decision) relate to damage taken?

Dataset

The dataset comes from UFC fight statistics available on Kaggle.

Each record represents a fight and includes:

Fighter names

Fight date

Fight result (win/loss)

Fight outcome method

Significant strikes landed

Significant strikes absorbed

Methods

The analysis was performed using Python (Pandas) for data cleaning and transformation.

Key steps included:

Calculating days between fights

Creating rest period categories (rest buckets)

Measuring damage taken using significant strikes absorbed

Aggregating statistics to analyze win rates and damage patterns

Visualizations

Interactive visualizations were created in Power BI, including:

Win rate by rest period

Average significant strikes absorbed by rest period

Damage absorbed by fight outcome

Tools Used

Python

Pandas

Google Colab

Power BI

GitHub

Key Insight

Initial analysis suggests that fighters who compete more frequently may have slightly higher win rates, while higher levels of damage absorbed are associated with lower performance outcomes.

Purpose

This project demonstrates skills in:

Data cleaning

Exploratory data analysis

Data visualization

Communicating insights from real-world datasets
