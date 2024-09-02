## Muellerian Anomalies and Gynecological Cancers
##This project is a collaborative research project between Montana State University (Dr. Miranda Margetts, Dr. David Hedges, and Bethany MacCarter) and Billings Clinic (Dr. Randy Thompson and Bethany MacCarter) , which is a hospital affiliate with data access to the Oracle Electronic Real World Database (OERWD).  
This project investigates the relationship of a population of patients with a muellerian anomaly and their prevalence of gynecological cancer as compared to a control population.  In order to compare these populations, a random forest model was used to assign propensity scores, which was then used to complete nearest neighbor matching using SciKitLearn.  
The project is currently under review, and if published, a brief summary of findings will be included here.
## Dependencies
##This project requires access to Oracle's Electronic Real World Database through the learning health network, healthedatalabs using PySpark notebooks within a Jupyter Hub.  This project utilized the June 2023 database.
## Code
##The notebooks are ordered 1-14, to follow the steps of database creation to random forest modeling use, propensity score matching and analyzing cancer outcomes.
Tables 1-2: Database creation using codes for mullerian anomalies (treatment and control populations)
Tables 3-9: Adding selected features (conditions/ procedures), and demographic information to each population.
Tables 10-12: This run a random forest model on all of the selected features, but after analyzing the feature rank analysis, selected features were consolidated and the random forest was run again.
Table 13- Propensity score matching using SciKitLearn.
Table 14- An analysis of the effect size for features, pre and post matching, along with cancer outcomes.

