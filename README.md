# dockerquickstart

Quickstart Dockerfiles and Sample Applications 
Quickstart to Docker run and GCP/Azure/AWS Kubernetes Engine deployments
I built these for training folks and thought would be useful make these available generally.

A bunch of Dockerfiles Their contents for docker and container beginners or simply to have fun.

Instructions for Ubuntu :
   apt-get install docker-ce

1. A Sample Helloworld Container

2. An Dockerfile and codes Web App Container that sends responds with fully messages from fortune
        docker pull hackacharya/hellomoo:latest
        docker run -d hackacharya/hellomoo:latest -
        
2. A Container image with an - Application that gets info from a Given URL and continously writes to disk
        docker run
        
3. A TCP Echo application
        docker pull hackacharya/tcpecho:latest

4. An SCTP Echo Applicaiton  
        docker pull hackacharya/stcpecho:latest
        
5. A Container to Show 


##Kubernetes YAMLS are also provided 
To deploy to your kubernetes cluster (AKS/GKE/AWS Kubernetes)

        
