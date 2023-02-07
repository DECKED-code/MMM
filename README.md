# MMM

**when starting SageMaker instance, make sure to stop when done**

run the code here:
https://us-west-2.console.aws.amazon.com/sagemaker/home?region=us-west-2#/notebook-instances/media-mix-model

Final model + ROAS Calc-v2
-bayesian version
-output saturation curves

MMM_production_v1.1
-production version that feeds into Tableau
-linear version
-output ROAS + marginal revenue

Steps to run MMM_production_v1.1
1) change offline data 
  -https://docs.google.com/spreadsheets/d/15TccSuBPBxy-yHIpXT_G8_1VpFpjOVpsPI2vBTjvZUs/edit#gid=0
  -https://docs.google.com/spreadsheets/d/1TpoiB9qm2lsBYDjLEfVeIjuE5_A-hRrsQoI_KHpsmw0/edit#gid=0
  -https://docs.google.com/spreadsheets/d/1ET3qENXybNMZkqpID6pqI16tDRxJqlQ6fczTVQBNVnE/edit#gid=0
2) change credentials for the snowflake authentication
3) change the params (follow instruction in the comments in code)

dashboard to visualize results
https://us-west-2b.online.tableau.com/#/site/decked/views/MMM/Summary?:iid=2
