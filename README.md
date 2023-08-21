# Python Flask - Demo Web Application 

In the process of learning DevSecOps, I made this very basic Gitlab CI/CD pipeline which contains some security checks.
The pipeline performs the following actions : 
  
    - Running tests in the application using Postman
    - Dependency scanning (SCA)
    - Container scanning 
    - Secret Detection
    - Static  Application Security Testing
    - Dynamic Application Security Testing
    - Building and pushing the docker image
    - Deploying the application in a remote server


For this demo, I used the following Python Flask web application : https://github.com/benc-uk/python-demoapp

The CI/CD Variables that should be added in Gitlab are :
- SSH_KEY :                   The private key for the server to which we intend to deploy
- REGISTRY_USER :             the Docker ID (the username to access Docker Hub )
- REGISTRY_PASS :             Docker Hub password
- DEFECTDOJO_API_KEY :        the API Key of Defect Dojo  


