# Case Analysis Capstone Project

This is a project-oriented course at the end of the Bay Path Applied Data Science masters program. Students will demonstrate their competence in the theory and practice learned from the program through the whole process of a complex data analysis project, including data collection, exploration, preparation, analysis, interpretation and presentation.


# Term Life Insurance Lapse Prediction

This project was done on behalf of and in collaboration with LL Global, Inc.  They provided real, anonymized policy data collected from their member insurance compaines.
Due to the sensitive nature of the data, insights and outcomes, an NDA is required to view the presentation.

Abstract:
The lapse of a term life insurance policy means the forfeiture of benefits to the policy holder.  To the insurer, it means the loss of revenue and potentially the customer of additional products.  This project utilizes simple and advanced binary classification machine learning algorithms for lapse modeling with real, anonymized policy data that was down-sampled to overcome class imbalance.  It was shown that ensemble tree methods (bagging, random forest, gradient boosting) outperformed logistic regression and single decision trees in terms of accuracy, recall and precision.  The gradient boosted (with XGBoost) model performed the best, showing that predicting term life insurance lapse is plausible with the provided policy and demographic variables.  Each ensemble method placed the greatest importance on the same three characteristics: the face value of the policy, the estimated current age of the policy holder and the estimated number of years the policy is active.

Highlights:

●	Achieved 78% recall, 66% accuracy, and 49% F1 Score with XGBoost despite unavailability of key variables, notable policy term length and date of data extraction (to   
  enable actual length of term completed, current age, etc.)

● Identified 13% of their member companies’ active policy holders as high risk (over 70% likely); met weekly to discuss project progress, strategies and insights 	
