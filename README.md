# Data Champion Leaderboard Analysis

- This project analyzes and merges data from two datasets, Basic Screening and Advanced Screening, to create a leaderboard based on total scores, percentages, and rankings. 
- The final output is an Excel file with color-coded scores for easy interpretation.


# Table of Contents

1.Project Overview
2.Datasets
3.Methodology
4.Features and Outputs
5.Requirements
6.Setup and Execution
7.File Structure
8.Future Improvements

# Project Overview

- The goal of this project is to:

1.Merge two datasets (DataSet1 - Basic Screening and DataSet2 - Advanced Screening) based on participant names.
2.Calculate Total scores, Percentages and Rankings for all participants.
3.Ensure consistency by including missing participants with default values.
4.Apply color coding to the scores to enhance data visualization.
5.Save the final leaderboard to an Excel file.
6.This project provides insights into participants' performance and simplifies leaderboard generation.

# Datasets

- The analysis uses 2 datasets provided in an Excel file:

1.DataSet1 - "Basic Screening":

- Contains scores from the basic screening process.
- Key columns: "Name" and "Total".

2.DataSet2 - "Advanced Screening":

- Contains scores from the advanced screening process.
- Key columns: "Name (Pls enter the same name as you did in preliminary screening)" and "Total".



# Methodology

# Step 1: Import Datasets

- The two sheets from the Excel file are imported using pandas.

# Step 2: Rename Columns

- Column names are standardized to avoid conflicts during merging.

# Step 3: Merge Datasets

- The datasets are merged on the Name column (renamed for consistency) using an inner join to combine only common entries.

# Step 4: Calculate Scores

- Basic and advanced scores are added to compute the total score.
- Percentages are calculated based on a predefined maximum score (e.g., max_score = 30).

# Step 5: Assign Rankings

- Participants are ranked based on their total scores in descending order.

# Step 6: Color Coding

- A color-coding function is applied to the total scores:

- (i) Red for scores below 50.
- (ii) Yellow for scores between 50 and 74.
- (iii) Green for scores 75 and above.

# Step 7: Output Final Leaderboard

- The final leaderboard includes the following columns:

- Serial Number (SL No)
- Name
- Basic and Advanced scores
- Total score
- Percentage
- Color
- The leaderboard is saved to an Excel file for easy distribution.


# Features and Outputs

1.Features

- Dynamic Handling of Rows: Automatically identifies participants present in both datasets.
- Color-Coded Scores: Enhances readability by visually differentiating scores.
- Customizable Maximum Score: Allows adjustments for different scoring schemes.

2.Final Output

-The final leaderboard is saved as an Excel file, Leaderboard_Output.xlsx, with the following structure: I name it as - "Final_Output_Leaderboard_Dataset"



" For More Detail Contact " :

1.Email: vijaygurung555@gmail.com &

2.GitHub: https://github.com/Vijaygurung1

3.Linkedin : https://www.linkedin.com/in/vijaygurung1/
