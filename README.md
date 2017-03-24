# CloudFormation Exercise

## What

This repo is a simple exercise of using CloudFormation to deploy a wordpress service using ansible.

## Deliverable

- Use CloudFormation to provision AWS resources to result in a running wordpress service.
- Use Ansible to automate the deployment of wordpress.


## Setup 

```shell
> git clone https://github.com/davidx/cloudformation-exercise
> cd cloudformation-exercise
```

## Run

```shell
> aws cloudformation create-stack --stack-name wordpress-test22 \
--template-body file://wordpress.json \
--parameters file://parameters.json --region us-west-1    
```
