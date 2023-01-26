# Chi2-test-in-Python

This project assesses the relationship between voting in the last political elections and the internet use frequency among 1470 Dutch respondents. 

#Workflow steps
1. Subset the data by rows and columns of interest
2. Summary stats 
3. Recoded the variables in a meaningful way
4. Non-substantive categories (e.g., people not eligible to vote or those that refused to answer) were coded as missing
5. Converted the variables to categorical 
6. Preliminary crosstabs
7. Chi-square test of independence and Cramer’s V (researchpy package)

#Findings

The estimates (Chi2(4) = 82.50, p < .05) showed a statistically significant association between the use of internet and the likelihood to vote in the last national elections. However, the magnitude of this relationship is week Cramer's V = 0.09.


