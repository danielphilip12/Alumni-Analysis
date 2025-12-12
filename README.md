# Alumni-Analysis

## Problem Statement
- This dataset contains various information about alumnis for a school, such as gender, diploma type, salary, etc. 

- The purpose of this analysis and predictie modeling it so see which alumni will default on their payment. 

## Data Dictionary
Include a data dictionary to explain the meaning of each variable or field in the dataset. You can also link to an external data dictionary.

| Column Name | Description |
|-------------|-------------|
| Year Graduated     | The year the alumni graduated |
| Gender     | Gender of the alumni (Male/Female) |
| Marital Status         | Whether the alumni is Married, Single, or Divorced         |
| Diploma Type         | Type of diploma earned (Standard or College Prep)         |
| Defaulted         | Whether the alumni defaulted or not         |
| Salary         | Salary of the alumni         |
| Fee         | Fee the alumni pays         |
| Savings ($)         | How much money the alumni has saved         |

## Executive Summary

### Data Cleaning Steps
The `Gender` column had a clearical error where some male alumni had 'M' entered instead of 'Male'. This was fixed.

I also had to fix the `Savings ($)` column to convert it to a float, as it was originally a string. 

### Key Visualizations
Include key visualizations that highlight important aspects of the data. Use graphs, charts, or any other visual representation to make your points.

#### Visualization 1: [Title]
[Description and interpretation of the first visualization.]

![Visualization 1](path/to/image1.png)

#### Visualization 2: [Title]
[Description and interpretation of the second visualization.]

![Visualization 2](path/to/image2.png)

## Conclusions/Recommendations
I performed predictive modeling with 3 types of algorithims: Logistic Regression, K Nearest Neighbors, and Random Forest. 

The results are below. 

| Model | Accuracy Score |
| ----- | -------------- |
| Logistic Regression | 0.59 |
| KNN | 0.45 |
| Random Forest | 0.55 |

The Logistic Regression model performed the best, accurately predicting the defaulting status 59% of the time. 

## Additional Information
Include any additional information, references, or resources that might be relevant for understanding the analysis.

---

Feel free to replace the placeholders with your actual content. Additionally, if you have images for your visualizations, make sure to replace the placeholder paths with the correct file paths or URLs.

Once you've filled in the content, save the file with a `.md` extension (e.g., `README.md`). You can use this Markdown file on platforms like GitHub to provide a well-structured README for your analysis.
