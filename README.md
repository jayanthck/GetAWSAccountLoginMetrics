# AWS Account Login Monitoring 

### Description 
This Repo contains cloud formation template to capture the number of AWS account login 

### Prerequisite
Enable CloudTrail logs

## ![Architecture](https://github.com/jayanthck/GetAWSAccountLoginMetrics/blob/master/Architecture.png)

### Deploy
```
aws cloudformation deploy --stack-name accountLoginMetrics --template-file ./accountLoginMetrics.yaml --capabilities CAPABILITY_NAMED_IAM
```