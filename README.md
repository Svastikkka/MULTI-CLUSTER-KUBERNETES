<h1>Micro Services App</h1>

<span style="color:#cc0000">Multi containerize application.</span>
> Combination of React, Redis, Postgres, Express and Node. Multi container app setup with docker and travis CI/CD pipeline. Using images on docker hub to deploy app directly into AWS and GCP
## Prerequisites

* [Docker](https://www.docker.com) - Containerization of App
* [Minikube](https://kubernetes.io/docs/setup/learning-environment/minikube/) - For running Kubernetes locally inside VM
* [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) - The Kubernetes command-line tool



## Tech Stacks
* [Docker](https://www.docker.com) - Containerize app
* [Docker Compose](https://docs.docker.com/compose) - Local development environment to run tests and builds by using volumes and networks
* [Docker Hub](https://hub.docker.com/) - Convenient Images
* [NGINX](https://www.nginx.com/) - Web Server
* [Create React App](https://github.com/facebook/create-react-app) - Bootstrapping
* [Node](https://hub.docker.com/_/node) - Backend
* [Redis](https://redis.io/) - Memcached
* [PostgreSQL](https://www.postgresql.org/) - Database
* [Travis-ci](https://travis-ci.com/) - CI/CD Pipelines
* [Kubernetes](https://kubernetes.io/) - Kubernetes



## Instructions


* <b> Step 1 Start minikube</b>- 
``` shell
minikube start
``` 
* <b> Step 2 Check Status</b>-
``` shell
 minikube status
``` 
* <b> Step 3 Run following command outside of folder</b>-
``` shell
kubectl apply -f k8s
``` 
* <b> Step 4 Run following command to check minikube ip</b>-
``` shell
minikube ip
```
* <b> Step 5 Run following command outside of folder</b>-
``` shell
check browser [minikube IP Address]:31515
``` 

### Application Architecture

Created using [App Diagram](https://app.diagrams.net/)
<div align="center">  
  <img alt="Application Architechture" src="screenshots/Travis Application Architechture.png"/>
</div>

### Deployment Architecture
Created using [App Diagram](https://app.diagrams.net/)
<div align="center">  
  <img alt="Deployment Architecture" src="screenshots/Travis Deployment Architecture 2.png"/>
</div>

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
