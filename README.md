# HelloDockerK8sWeb
Basic project using Docker and Kubernetes to deploy a simple web application

## Apply the manifests to your Kubernetes cluster:
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## Access the Web Application:Get the external IP and port to access the web application:
kubectl get services

Open a web browser and navigate to <external_ip>:<node_port> (e.g., http://external_ip:30000). We can see "Hello, Docker and Kubernetes!" displayed.

This project demonstrates how to containerize a web application using Docker, deploy it to a Kubernetes cluster, and expose it externally using a NodePort service.
