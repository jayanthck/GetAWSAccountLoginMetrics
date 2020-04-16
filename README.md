# AWS Account Login Monitoring 

## This Repo contains cloud formation template to capture the number of AWS account login 

## Prerequisite
 Enable CloudTrail logs

## ![Architecture](http://url/to/img.png)

## Deploy
```
aws cloudformation deploy --stack-name accountLoginMetrics --template-file ./accountLoginMetrics.yaml
```