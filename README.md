# MentalHealth


## Analyzing Students' Mental Health in SQL
## Introduction
This workspace focuses on analyzing students' mental health using SQL queries. The dataset comes from a Japanese international university that surveyed its students in 2018 and published a study on mental health difficulties among international students. The study identified social connectedness and acculturative stress as predictive factors for depression.

The goal of this project is to explore the dataset using PostgreSQL to determine if international students indeed face a higher risk of mental health difficulties and whether the length of stay plays a significant role.

## Dataset Description
The dataset contains information on various factors related to students' mental health. Here's a brief description of some relevant columns:

inter_dom: Types of students (international or domestic)
academic: Current academic level (undergraduate or graduate)
age: Current age of student
stay: Current length of stay in years
todep: Total score of depression (PHQ-9 test)
tosc: Total score of social connectedness (SCS test)
toas: Total score of acculturative stress (ASISS test)
Steps
## Loading Data: The project begins by loading the dataset from a CSV file named students.csv.

## Exploring Data: The data is explored to understand its structure and columns.

Average Scores by Length of Stay: SQL queries are used to calculate the average scores of depression, social connectedness, and acculturative stress based on the length of stay for international students. The results are presented in descending order of stay length.

## Running the Queries
To run the SQL queries and analyze the dataset:

Open your preferred SQL environment.
Load the dataset using the query provided (SELECT * FROM 'students.csv';).
Run the queries for exploring and analyzing the data.
## Conclusion
Through SQL queries, this project aims to determine whether international students have a higher risk of mental health difficulties and if the length of stay contributes to this risk. By analyzing the dataset, you can gain insights into the mental health challenges faced by international students in a different country.

