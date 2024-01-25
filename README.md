# Jamboree-Education---Linear-Regression
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.


Problem Statement

Help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. Also help in predicting one's chances of admission given the rest of the variables.
Column Profiling:

Serial No. (Unique row ID)
GRE Scores (out of 340)
TOEFL Scores (out of 120)
University Rating (out of 5)
Statement of Purpose and Letter of Recommendation Strength (out of 5)
Undergraduate GPA (out of 10)
Research Experience (either 0 or 1)
Chance of Admit (ranging from 0 to 1)

Concept Used:

Exploratory Data Analysis
Linear Regression
Insights
1)Multicollinearity is present in the data.
2)After removing collinear features there are only two variables which are importantin making predictions for the target variables.
3)Indepedent variables are linearly correlated with dependent variables
Recommendations
1)CGPA and Research are the only two variables which are important in making the prediction for Chance of Adm
2)CGPA is the most important varibale in making the prediction for the Chance of Admit.
3)Following are the final model results on the test data:
RMSE: 0.07
MAE: 0.05
R2_score: 0.81
Adjusted_R2: 0.81
