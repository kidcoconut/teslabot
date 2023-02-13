# Tesla Sentiment Analysis
The mission:  a colleague hs passed their Tesla sentiment analysis model to you and would like your help to deploy it to a production environment as a serverless application via AWS Lambda.


# Overview
This project:
-  Builds and deploys a model via SAM (Serverless Application Model) CLI
-  Implements an ML App on AWS Lambda
-  Deploys the ML App to a public endpoint


# References
https://github.com/FourthBrain/MLE-10/tree/main/assignments/week-14-model-serving


# AWS Details
Stack Name:     stk-wk14-tesla-sentiment-mckone-regEast
AWS Region:     us-east-1



# CloudFormation outputs from deployed stack
------------------------------------------------------------------------------------------------------------------
Outputs                                                                                                          
------------------------------------------------------------------------------------------------------------------
Key                 SentimentFunctionIamRole                                                                     
Description         Implicit IAM Role created                                                                    
Value               arn:aws:iam::387894657935:role/stk-wk14-tesla-sentiment-mck-                                 
SentimentFunctionRole-1239TF6376G7Y                                                                              

Key                 SentimentApi                                                                                 
Description         API Gateway endpoint URL for Prod stage                                                      
Value               https://nlxsrz1fmd.execute-api.us-east-1.amazonaws.com/Prod                                  

Key                 SentimentFunction                                                                            
Description         Sentiment Analysis Lambda Function ARN                                                       
Value               arn:aws:lambda:us-east-1:387894657935:function:stk-wk14-tesla-sentiment-mckone--             
SentimentFunction-DvqwoLE0T7fd                                                                    
