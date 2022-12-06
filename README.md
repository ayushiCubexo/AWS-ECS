# AWS-ECS

Deploy image of Flask app on AWS resources... 

1. Create a Docker image for the Flask application, you can find the required files in this repository.  

2. Upload this image to the Docker public registry and deploy it in multiple places:


3. Deploy the image in the ubuntu EC2 instance and expose it to the world using a load balancer. 
4. Deploy the image in ECS Cluster and expose it to the world using a load balancer. 

Points to follow :
Ensure the application is auto-scalable on the basis of the load. 
Configure the monitoring which include the info of CPU, Memory, Disk usage information.


Ensure you are using best practices for each solution.......
