[![Infrastruture Diagram](https://github.com/Cadmiral/cf_ecs_repo/blob/main/ecs-webapp.png?raw=true)](https://github.com/Cadmiral/cf_ecs_repo/blob/main/ecs-webapp.png?raw=true)
# AWS CloudFormation - Web App running on ECS Fargate 

## What is it?

This project deploys a Web App running in AWS ECS Fargate using CloudFormation templates, components are captured in the infrastructure diagram.

## How it works:

1. Build and upload docker image to ecr (https://docs.aws.amazon.com/AmazonECR/latest/userguide/getting-started-cli.html)
2. Deploy network-stack.yaml using CloudFormation
3. Deploy service-stack.yaml using CloudFormation
4. Go to CloudFormation -> click on the network stack -> Outputs -> click on LoadBalancerExternalUrl link
