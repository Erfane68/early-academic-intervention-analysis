# early-academic-intervention-analysis
A data analysis project evaluating dropout rates and GPA after early academic intervention in college students.
# Early Academic Intervention Project

## Project Overview
This project investigates the impact of an **Early Academic Intervention (EAI)** program on student dropout rates and academic performance at a college. The intervention provides additional tutoring, check-ins, and learning support to at-risk students. The goal is to evaluate if participation in this program reduces dropout rates and improves GPA and credits earned.

### Objective
- **Primary Objective**: To test whether offering early intervention significantly reduces student dropout rates.
- **Secondary Objective**: To test if the intervention improves academic performance (GPA and credits earned).

### Dataset
The dataset used in this project consists of information on:
- **Intervention Group**: Students who participated in the Early Academic Intervention program
- **Declined Group**: Students who were eligible but declined participation in the intervention
- **Control Group**: Students who did not participate in any intervention

The dataset includes:
- Dropout rates
- Program completion rates
- Average GPA
- Average credits earned

### Analysis
1. **Dropout Analysis**:  
   We use statistical tests like the **binomial test** and **proportion z-test** to determine if the intervention significantly reduces dropout rates compared to the control group.
   
2. **Academic Performance Analysis**:  
   We use **T-tests** and **ANOVA** to analyze if there are significant differences in the average GPA and credits earned across different groups (EAI Participated, EAI Declined, and Control).

### Results
- **Dropout Rates**: The intervention significantly reduced dropout rates when compared to the control group. The p-value from the proportion z-test was found to be 0.008696, which is below the 0.05 significance level, leading us to reject the null hypothesis.
  
- **Academic Performance**:  
   - **GPA**: A T-test revealed a significant difference in the average GPA between the EAI Participated group and the EAI Declined group (p-value = 0.0).
   - **Credits Earned**: Similarly, a T-test found a significant difference in the average credits earned between the EAI Participated group and the EAI Declined group (p-value = 0.0).

### Visualizations
The project includes the following visualizations:
- **Boxplots**: Showing the distribution of GPA and credits earned across the three groups (EAI Full, EAI Declined, and Control).
- **Binomial Distribution Plot**: Visualizing the probability of dropout rates based on the intervention's success.

### Installation
To run the analysis and visualizations, ensure you have the following Python libraries installed:
- numpy
- scipy
- pandas
- matplotlib
- seaborn
- statsmodels
