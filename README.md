# Recruitment Insights

## Project Overview
The Recruitment Insights Dashboard is designed to analyze recruitment data and provide actionable insights into various metrics related to recruiters and salaries. The dashboard consists of two main pages that present visualizations for effective decision-making.

## Tools
- **Power BI**: For data visualization and dashboard creation.
  
- **Data Source**: Recruitment dataset sourced from Previous Internship.

- **Technologies Used**: DAX, data modeling, data transformation.

## Visuals
The dashboard provides a comprehensive view of recruitment data, enabling users to quickly assess performance and identify trends. Each visual serves a specific purpose, contributing to a holistic understanding of the recruitment process.

## EDA
### 1. Data Cleaning
- **Inconsistent Data Types**: Identified and standardized columns with mixed data types, such as text and numbers.
  
- **Missing Values**: Numerous missing values were found across various columns.
  
  - **Actions Taken**: 
    - Filled missing values in numerical columns with the mean.
    - Removed rows with excessive missing data to maintain dataset integrity.
      
- **Value Grouping**: Consolidated similar job titles to simplify analysis, ensuring uniformity across categories.
  
- **Data Transformation**: Converted date formats into a standardized format to facilitate time-based analysis.

### 2. Data Distribution
- **Age Distribution**: 
  - Most candidates fall within the age range of 25-35, with a noticeable decline in recruits over 40.
    ![recru](https://github.com/user-attachments/assets/21fbb69d-1530-42bd-896e-bac947f6f7ee)

- **Salary Distribution**: 
  - The salary distribution shows a right skew, indicating a few high earners compared to the majority.
    ![recru2](https://github.com/user-attachments/assets/876d2771-27d5-4917-9f5f-b1df0131942f)

    
 
### 3. Data Distribution
- **Age Distribution**: 
  - Most candidates fall within the age range of 25-35, with a noticeable decline in recruits over 40.
    
- **Salary Distribution**: 
  - The salary distribution shows a right skew, indicating a few high earners compared to the majority.
 
### 4. Categorical Analysis
- Analyzed categorical variables (e.g., nationality, position).
  
- **Key Insights**:
  - The top three nationalities represented in the recruitment dataset are India, Filipino and Egypt.

### 6. Visualizations
- Included various visualizations in the dashboard, such as:
  
  - **Scatter Plot**: Relationship between average age and average expected salary by recruiter.
    
  - **Tree Map**: Salary distribution by the top five nationalities.
    
  - **Bar Charts**: Comparison of recruits by position and nationality.
 
## Limitations

I had to remove all null values from expected and PRT salary because they would have affected the accuracy of my conclusions from the analysis.
 
## Data Source
The dataset used for this analysis was obtained from a previous internship.
 


