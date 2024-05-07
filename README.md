# hw07-module3-aws

## ECR

### 1. Create your own ECR repo
![alt text](<screenshots/ecr/1/Знімок екрана з 2024-05-07 15-12-41.png>)
![alt text](<screenshots/ecr/1/Знімок екрана з 2024-05-07 15-15-51.png>)
![alt text](<screenshots/ecr/1/Знімок екрана з 2024-05-07 15-17-43.png>)
![alt text](<screenshots/ecr/1/Знімок екрана з 2024-05-07 15-18-22.png>)

### 2. Build your custom image on your laptop or in ec2
### 3. Login to ECR repo
### 4. Push image to ECR
### 5. Delete ECR


## ElastiCache

### 1. Create elasticache cluster
### 2. Create ec2 instance and provide policy which will allow this specifc ec2 access to your specific cluster
### 3. Install redic-cli or run redis container from the instance and connect to cache cluster
### 4. Put a few values to DB and get them
### 5. Delete elasticache cluster, ec2, ec2 policy


## SNS

### 1. Create SNS topic
### 2. Subscribe your email to notifications
### 3. Send message from web console to the topic
### 4. Send message from aws cli
### 5. Confirm that you've got both messages
### 6. Delete topic


## SQS

### 1. Create SQS queue
### 2. Send message from web console to the queue
### 3. Get message from aws cli
### 4. Send message from aws cli
### 5. Get message from web interface
### 6. Delete topic


## Secrets

### 1. Create secret from the web console
### 2. Get secret value from aws cli
### 3. Change secret value from aws cli
### 4. Get updated value from web console
### 5. Delete secret from aws cli without retention period