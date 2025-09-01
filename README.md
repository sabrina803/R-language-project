# R-language-project
## Project Overview
This project was completed as the final assignment for an R programming and data analysis course.  
The goal is to investigate the relationship between **gender, department, and admission outcome** using statistical modeling, and to predict admission probabilities with a logistic regression model.

## Dataset
- Public dataset: **Berkeley Admissions Data**  
- Contains applicant gender, department, and admission results  
- Cleaned and pre-processed for reproducibility  

## Methods
- Data cleaning and visualization (`dplyr`, `ggplot2`)  
- Statistical hypothesis testing (Chi-square test)  
- Logistic regression modeling (`glm`, `binomial`)  
- Bootstrap confidence interval estimation  
- Model evaluation (AUC, confusion matrix)  

## Key Findings
- Overall, male applicants had a higher admission rate than female applicants.  
- After controlling for departments, the gender gap narrowed, suggesting **department choice** was the primary driver of admission outcomes.  
- The logistic regression model showed good performance, with AUC = 0.82 (example).  

## Skills Demonstrated
- Data processing and modeling in R  
- Statistical inference and hypothesis testing  
- Data visualization with `ggplot2`  
- Report writing with R Markdown  
