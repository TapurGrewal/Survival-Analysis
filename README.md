# Survival-Analysis
Survival analysis of lung cancer

Survival Analysis:
Survival analysis is a branch of statistics which is mainly used for understanding the expected duration or time till an event (which might include death, failure of a product etc.) will occur.

Role of Survival Analysis in Cancer Studies:
In this case, the main motivation is to find out the clinical characteristics (age, gender, etc.) of a patient (with lung cancer) on which his/her survival depends.

Types of Models used in Survival Analysis
There are different types of ways in which we can perfrom survival analysis. It is perfomed in several ways like when we define a group. Some of them are Kaplan Meier Curves, Cox Regression Models, Hazard Function, Survival Function etc.
When the survival Analysis is done to compare the survival analysis of 2 different groups, we typically tend to use a Log-Rank test.
When the Survival Analysis is done to describe the categorical and quantitative variables on survival we tend to use a Cox proportional hazards regression, Parametric Survival Models etc.

Survival Probability and Survival Function:
Survivability:
Survival Function  S(t)=P(T>t) , Probability of survival beyond time 't'

Hazard and Hazard Ratio
Hazard:
HAZ=P(T<t+δ|T>t) , Probability of dying in the next few second ( δ  seconds), considering the subject is alive at the moment.

Hazard Ratio  (HR)=HAZ, x = 1HAZ, x = 0 
Here, Hazard ration basically, gives an idea about the relative hazards i.e., the hazard of a group who are exposed to some event  x=1  to the group who are not exposed i.e.,  x=0 


Overview of the Kaplan-Meier Estimation
The Kaplan-Meier estimator is a non-parametric statistical model used to estimate the survival function (probability of a person surviving) from the lifetime data. Here the KM model is being used to measure the fraction of patients living for a specific time after treatment or diagnosis of the cancer.

Kaplan-Meier Equation
S(ti)=S(ti−1)∗(1−dini)

In a more generalized way, the probability of survival for a particular time can be given as:

St=Number of subjects at risk at the start−Number of subjects that diedNumber of subjects at risk at the start
 
Survival probability follows the concept of conditional probability, where for a person to be alive on the nth day, he should have been alive for the last n-1 days. Hence we are looking at the past values also, and the probability of the nth day depends on the probability of the previous days.

So to summarize, from the above equation we get:
S(n)=S(1)∗S(2)∗S(3)∗...∗S(n−1)∗S(n)

Result Interpretation:
From the graph, it can be seen that the subject 14 has the highest chances of survival and subject 10 has the lowest chances of survival. Looking into the ph.ecog values in the table above, it can be seen that subject 14 has a low ph.ecog value (1.0) compared to subject 10 (3.0).
