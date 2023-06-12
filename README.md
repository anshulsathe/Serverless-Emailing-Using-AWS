# Serverless Emailing using AWS

this project can be used to send emails to senders using AWS. This is better than a normal email since we can schedule or trigger emails according to our demand. We have to keep in mind that the two tools that are used in this project are Amazon Simple Emailing Service (SES) and AWS Lambda.

## Steps of implementation
- First create a Lambda function and select Python 3.8 in the Runtime menu. 
- Now we will have to create a new permission for our lambda function to access SES. To do this go to configuration tab in the lambda function and go to premissions. We can see that a default role is created for the function called "ses-email-role-u412n10d". Click on this role and we will be redirected to a new IAM Console page.
![App Page](https://github.com/anshulsathe/Serverless-Emailing-Using-AWS/blob/main/Screenshot%20(128).png)
