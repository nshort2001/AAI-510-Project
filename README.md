# Predicting Diabetic Patient Readmission Improving Patient Outcomes and Reducing Hospital Costs 

Authors and Contributors: Nicholas Short & Ahmed Ibrahim Ahmed

# Description: 

Hospital readmission is a costly venture for the American Medical System. It takes a toll on the financial stability as well as the operational efficiency of the hospital. Given how many paitents hospitals treat per day on average, necessitating paitents that need further treatment after discharge disrupts the flow of care.
Looking at what we can do to levergae ways to minimize this utilizing Machine learning we have assembled a parntership to tackle the sigsn and indicators that lead to readmission of diabetc paitents adn help to determine the symptoms and factors that need to be treated to avoid further readmissions whether that be within 30 days of discharge or more.

Our results yeilded an overall accuracy of predictions of up to 60%, breaking the many uncertainties taht come with a long form diagnosis process and greatly shortens the discourse needed to make sure that the paitent is getting the care that they need so that they may live a good life. 
Ensuring that people are living happy lives is the goal of the docotrs, nurses, technicians and lab staff in each hospital. To ensure that, beign able to operate in an effective way with the best equipment will help to make surethat both for the paitents and the doctors that the hsopital is providing care suitable to th paitent and of the expertise of the workers.

All preprocessing results, analysis, model comparisons and model tuning and steps are provided in the IPYNB file in the repository


# Analysis Statisitcs:

![image](https://github.com/nshort2001/AAI-510-Project/assets/142278565/2d6a4de5-a9d4-471e-a896-79c2ffd4c00f)

# Post Model Tuning Statistics:

Accuracy: Decreased from 0.60 to 0.58

Precision: Decreased from 0.58 to 0.56

Recall: Decreased from 0.60 to 0.58

F1-score: Decreased from 0.56 to 0.53

ROC-AUC: Decreased from 0.69 to 0.64

# Conclusions:

The overall performance metrics of the three models (accuracy, precision, recall, F1-score) suggest that the models are only moderately successful at predicting readmissions. There is still a significant room for improvement readmissions.

The Gradient Boosting Classifier emerged as the best performing individual model with an accuracy of 0.60 and a ROC-AUC of 0.69, indicating its capability to handle the complexity and imbalance in the dataset better than other models.

# Data Source: 
Clore,John, Cios,Krzysztof, DeShazo,Jon, and Strack,Beata. (2014). Diabetes 130-US Hospitals for Years 1999-2008. UCI Machine Learning Repository. https://doi.org/10.24432/C5230J.
