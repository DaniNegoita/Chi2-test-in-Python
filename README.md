# Chi2-test-in-Python

This project assesses the relationship between voting in the last political elections and the internet use frequency among 1395 Dutch respondents. 

#Workflow steps
1. Subset the data by rows and columns of interest
2. Summary stats 
3. Recoded the variables in a meaningful way
4. Non-substantive categories (e.g., people not eligible to vote or those that refused to answer) were coded as missing
5. Converted the variables to categorical 
6. Preliminary crosstabs
7. Chi-square test of independence and Cramer’s V (researchpy package)

#Findings

The estimates (Chi2(4) = 13.10 p < .05) showed a statistically significant association between the use of internet and the likelihood to vote in the last national elections but the magnitude of this relationship is weak Cramer's V = 0.10. All, exception made for three expected frequencies cells, were greater than five. 


