# Trend Micro Vision One Container Security 

This json CloudFormation Template creates the following AWS Service:

1. ECS 
2. Task Definitions ( Based on your ECR Image )
3. Service defined to run a single Container instance

## Getting Started:

When utilising this template, you need to edit and define the commented areas to your requirements. This includes region for your AWS Logs, URI for your image file, ARN for the IAM role for the execution of the service, as well as security group ID and subnet ID.

Additional optional variables include the port mapping for the container. In this example port 80 is used.

## Assumptions

This project assumes that you have already deployed the Vision One Container Security cloudformation Template and inegrated your AWS Account within the platform. It is recommended that all features are deployed for full visibility and telemetry to be sent to the Vision One platform:

<img width="600" alt="image" src="https://github.com/robinp77/tm-v1-containersecurity/assets/63721250/66bc9435-b5dc-435f-8f3b-59f16584b37a">


It also assumes that you have already created an Amazon Elastic Container Registry ( ECR) and have pushed an image to your repository. For details on pushing a docker image to ECR, please see here: 
https://docs.aws.amazon.com/AmazonECR/latest/userguide/docker-push-ecr-image.html


Feedback and contributions welcome!

