Take a web application in a language of your choice, preferably Java,Python, Nodejs or PHP. This need not be written from scratch. There are tons of them available in Github.
- Create a Dockerfile for building a container image for the application.
- Create a docker-compose file for local setup of the application. Ex: A Python application might use a DB. So, you might need to setup the python container and the DB container in the docker-compose file.
- Spin up a Kubernetes cluster in any cloud provider. You can get free credits to spin up a Kubernetes cluster if you sign up in AWS, DigitalOcean, Azure and Linode.
- Create YAML artifact files to deploy your application in Kubernetes. Test this on your local machine with Minikube or Kind.
- Create a CD pipeline(in Github actions or Gitlab CI) to deploy any app changes to the Kubernetes cluster automatically. This will involve building a new tag of the application container image, then deploying it to Kubernetes.

## Optional steps
These are optional steps but fetch more brownie points if done.
Terraform script to spin up the Kubernetes cluster.
Use of Helm charts to deploy the application.
Demonstrate Horizontal pod Autoscaler.
Deploy additional services, like Redis or ElasticSearch.
Add basic test cases in the CD pipeline.
Container image vulnerability scanning in the CD pipeline. 
