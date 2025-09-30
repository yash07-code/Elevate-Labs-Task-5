
### 1. Start Minikube
```bash
minikube start --driver=docker
minikube status
kubectl version --short

### Apply the deployment:
kubectl apply -f deployment.yaml
kubectl get deployments

###Apply the service:
kubectl apply -f service.yaml
kubectl get svc

kubectl delete -f deployment.yaml -f service.yaml
minikube stop
minikube delete
