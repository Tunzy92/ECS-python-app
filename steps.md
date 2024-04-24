Elastic Container Service

What is AWS ECS?

Elastic Container service is a managed container ochestrastion service that helps you to deploy and manage containerized applications.

demo and steps with a simple python application
1. create a cluster and leave everything else as default
2. login to your ECR repository.
3. on your github repository, you have your dockerfile on your repo, build your docker image and tag the image with the ECR repo tag and push the image.

TO DEPLOY CONTAINER IMAGE ON ECS, you need a task definition.
On ECS
1. create a task definition and integrate with Cloudwatch
in one of the sections of task definition, input your container name and container URL and container port, including port mapping (80, 443)
2. in your Task Definition, in your Deploy section, once your Task Definition is active, you need to RUN TASK
3. go to ECS Cluster and refresh.

That's how you deploy your application on ECS Cluster.
