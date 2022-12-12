# bhanu-prakash-mediawiki-maria-db
This is mediawiki setup procedure. Using this document we can deploy mediawiki in AWS EKS.
## Overall approach:
Entire workflow has been implemented using GITHUB Actions pipeline 
1. Resources provisioning using AWS CFT
2. Docker images build and publish to AWS ECR
3. Deployment of applications to kubernetes using deployment and service yaml files
4. Creation of replica's with specified memory limits 
5. Mounting of files to different pods using configmap in a different namespace 

![image](https://user-images.githubusercontent.com/25173384/207126134-0b437cfd-5213-4a33-b793-627a5515be2d.png)
![image](https://user-images.githubusercontent.com/25173384/207125507-9ce5ad6a-a7ff-4e0e-a2b5-bdef7865a60e.png)
![image](https://user-images.githubusercontent.com/25173384/207125573-bdbdc038-e1cd-4b9e-98f3-8f3eb769a1e7.png)
![image](https://user-images.githubusercontent.com/25173384/207125791-65640ba4-98a6-4f2d-bc68-6005c4e81b0a.png)
![image](https://user-images.githubusercontent.com/25173384/207125874-d46dbc95-5031-453a-9379-8008fb7d71e8.png)
![image](https://user-images.githubusercontent.com/25173384/207125938-066c13b1-e937-4f9d-948f-e59a19a7e093.png)
![image](https://user-images.githubusercontent.com/25173384/207123490-b00aff19-6866-4c1e-8fe9-f61a1a418202.png)
![image](https://user-images.githubusercontent.com/25173384/207123612-ee3f0d84-2dbd-441d-b901-8646baa7d933.png)
![image](https://user-images.githubusercontent.com/25173384/207123876-8be5b41a-ab5a-4964-b56e-06b0d2c65af2.png)
![image](https://user-images.githubusercontent.com/25173384/207123953-0614e3c5-3563-461a-b1a5-7956363b3f4a.png)
![image](https://user-images.githubusercontent.com/25173384/207124017-5ab0d6ef-0e49-4607-a546-86a4ef0393ae.png)
