# Python-with-AWS-Lambda  
We are using AWS cloud watch in combination with AWS Lambda Function.  
We are Triggering a Lambda function when an Amazon Elastic Block Store (EBS) volume is created. We use Amazon CloudWatch Events.  
On creation of let's gp2 EBS volume the lambda function automatically convert it to the type gp3 EBS volume.    
We need to provide IAM roles permission to EBS volume policy to modify the volume.  
Also we are using BOTO3 python library to convert the gp2 EBS volume to gp3.  
