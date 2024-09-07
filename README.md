# <p align="center">Kubernetes</p>

## begin with kubernetes 

when a node fails how do move the workload of the field node to another worker node? -> Thats where the Master comes in.

The Master is another node with Kubernetes installed in it and is configured a Master. 

with installing a Kubernetes Service, that be installed Services with name : 
API SERVER, etcd, kubelet, Container Runtime, Controller, Scheduler, API Server 

API Server: act as frontend for kubernetes
etcd key store : a reliable key value store used by Kubernetes to store all data used to manage the cluster.
Scheduler : is a responsible for distributing work or containers across multiple nodes.
Controller : the controllers are the brain behind orchestration. they are responsible for noticing and responding when nodes, container or end points goes down. 
Container Runtime : The Container Runtime is the underlying software that is used to run containers. it happens to be Docker.
kubelet : Agent that runs on each node in the cluster. The agent is responsible for making sure that the containers are running on nodes as expected. 


`kubectl run hello-minikube`

The kubectl run command is used to deploy an application on the cluster.

`kubectl cluster-info`

The kubectl cluster info command is used to view information about the cluster.

`kubectl get nodes`

is used to list all nodes part of the cluster.




