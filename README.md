# bhanu-prakash-mediawiki-maria-db
This is mediawiki setup procedure. Using this document we can deploy mediawiki in AWS EKS.
## Overall approach:
Entire workflow has been implemented using GITHUB Actions pipeline 
1. Resources provisioning using AWS CFT
2. Docker images build and publish to AWS ECR
3. Deployment of applications to kubernetes using deployment and service yaml files
4. Creation of replica's with specified memory limits 
5. Mounting of files to different pods using configmap in a different namespace 
