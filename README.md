# (No Show Appointments Dataset Investigation Project)
## by (Kommomo Usang)


## Dataset

This dataset contains data associated with data associated with 100k medical appointments in Brazil. The dataset was gathered from the url-https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv. This project was focused on ascertaining why only 30% of patients did not show up for their medical appointment. To tackle this question/problem, i analysed the factors that could determine the likelihood of a patient showing up or not. This was done using 5 questions which were asked in the course of the project. Three independent variables were analysed alongside one dependent variable. My dependent variable 'no_show' or 'show' says returns No if the patients showed up for their appointment and Yes if they did not show up. In a bid to understand the structure of the data and fix it, i assessed and inspected the data to identify problems with it that need to be fixed...problems such as incorrect datatypes, missing data, duplicate rows, mismatch number or records,structural problems etc. Adequate cleaning of the data will be performed where necessary as soon as assessing is done

## Installation

> To run this code, you will need an installation of python and the following librarers-
- pandas
- numpy
- matplotlib
- csv file

## Summary of Findings

> In the course of my exploratory data analysis, i asked some relevant questions, selected the variables(Age, gender and scholarship) which i assumed would be relevant to answering the questions and created adequate visualizations that were focused on supporting my assumptions and addressing the questions. The following findings were made-
- It cannot be concluded that a particular gender is more likely to show up for their appointment as there is no significant correlation between gender and patient show up status
- Access to Scholarship reduces the likelihood of a patient showing up for their appointment. We have seen that those with access to scholarship were less likely to show up for their appointment
- A particular age group influences whether a patient shows up or not. Childen(0-10years) are more likely to show up for their appointment
- There is a strong correlation between age and scholarship in determining show or no show. Younger children(0-10years) who do not have access to scholarship are more likely to show up for their appointment
- There is a relationship between scholarship and gender which influences show or no show. Male Patients with Scholarship have the highest likelihood of showing up for their appointment
- The most important factors affecting whether a patient will show up for their medical appointment are Age and Scholarship.
