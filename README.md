<h1>Micro Services App</h1>

## Prerequisites

* [Docker](https://www.docker.com) - Containerization of App
* [Minikube](https://kubernetes.io/docs/setup/learning-environment/minikube/) - For running Kubernetes locally inside VM
* [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) - The Kubernetes command-line tool

##Instruction

* <b> Install Prerequisites </b>- Most important, install all the requirments mention above 
* <b> Step 1 Start minikube</b>- 
``` shell
minikube start
``` 
* <b> Step 2 Check Status</b>-
``` shell
 minikube status
``` 
* <b> Step 3 Start minikube</b>-
``` shell
kubectl apply -f multi-cluster-kubernetes--master
``` 
