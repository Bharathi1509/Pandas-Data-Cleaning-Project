# Sports Data Cleaning and Analysis using Pandas

## Overview

This project focuses on cleaning, validating, and analyzing a raw sports dataset using Python and pandas.
The dataset intentionally contains common real-world data issues such as duplicates, missing values,
inconsistent formats, invalid ranges, and typographical errors.

Primary goal: Data cleaning and preprocessing  
Secondary goal: Basic exploratory data analysis

---

## Dataset Description

The dataset represents match-level and player-level sports data and includes fields such as:

- Player_ID, Player_Name, Age, Gender, Country
- Sport_Type, Team, Position, Coach_Name
- Match_ID, Match_Date, Venue, City
- Score, Goals, Assists, Wickets, Minutes_Played
- Match_Fee, Bonus, Sponsorship_Amount
- Ticket_Sales, Ticket_Type, Payment_Mode
- Win_Status, Feedback_Score, Rating
- Fan_ID

The raw dataset is assumed to be noisy and unclean.

---

## Key Features

### Data Cleaning
- Removed duplicate rows and duplicate IDs
- Handled missing values using defaults and statistical methods
- Standardized date formats to YYYY-MM-DD
- Corrected typographical errors in categorical columns
- Standardized text data (lowercasing, trimming spaces)
- Removed invalid or unrealistic numeric values
- Dropped irrelevant columns and incomplete records

### Feature Engineering
- Created Total_Earning, Performance_Score, Revenue
- Categorized players into Age_Group and Performance_Level
- Encoded categorical variables (Gender, Win_Status)

### Analysis
- Top players by earnings and sponsorship
- Average ratings by sport type
- Team-wise and country-wise summaries
- Outlier detection using IQR
- Venue, payment mode, and match condition analysis

---

## Technologies Used

- Python 3
- pandas
- Jupyter Notebook

## Output
-Cleaned Dataset

##Author
BHARATHI
