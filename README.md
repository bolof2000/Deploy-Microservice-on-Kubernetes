# Deploy-Microservice-on-Kubernetes

Commands:
minikube status  -- Check Minikube status 
minikube start --- Start Minikube
kubectl apply -f podfile.yaml -- apply changes to the pod files
kubectl apply -f webapp-service.yaml  -- apply changes to the service file
 kubectl get all -- check running pods 
 kubctil describe svc 
 kubctl get pods -- get list of pods
 kubctl get po --show-labels - show each labels in the pod
 kubctil get po --show-labels -l release=0  - get a specific release in a pod
 
