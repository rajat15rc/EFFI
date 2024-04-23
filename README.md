Predict Home Credit Default Risk for an applicant in loan application though an automated ML model, and then perform in-depth analysis of how the model is predicting those decisions against each instances. 
Algorithims and Methods: 
* Feature Selection and other Data Preprocessing Steps including Imputation(KNN Imputer, etc.)
* Normalisation
* XGBoost
* Feature Weights given by model and Prediction Confidence for each decision
* Causal Discovery Algorithm (SAM - CDT Lib) including Indegree and Outdegree of each feature
* Selection Rate of Each Feature (Fairlearn)
* Feature Combinations Selection Rate
* Comparison of Different Applications (How Similar each application is)
* Converting Each Step into a format that is easily understandable to a non-technical end-user 

Results: 
* Models (XGBoost, CDA) and Datasets (Feature Combinations, Feature Similarities, etc.) were significant in running the userstudy and obtaining feedback.
* The model achieved an accuracy of 72% and a 0.72 consistency fairness index.


Feedback Analysis analyses the feedback given by participants: 

* Average number of clicks that a user did on a function with std
* How many times each application was viewed w.r.t each user
* Which attribute was most filtered for w.r.t each participant
* Which two application combination was the most seen w.r.t to each user
* Selected attribute in Causal graph w.r.t User
* Applications_Prediction_Confidence : Ascended or Descended w.r.t each User
* How many applications were rated as fair/unfair w.r.t to each participant
* How often they gave labels w.r.t each user
* How often they gave labels and weights to an application w.r.t each user
* How many times an application was rated by Users w.r.t each participant
* Unfairness ratio w.r.t each participant
* Mean and std of the suggested weight change for a feature w.r.t the original weight
* Descriptive stats for the participants
