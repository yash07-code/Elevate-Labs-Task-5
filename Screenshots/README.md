
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

<img width="1869" height="1004" alt="Screenshot from 2025-09-21 15-03-32" src="https://github.com/user-attachments/assets/558ed5ae-a100-4bde-bf92-867f5c645e62" />
<img width="1867" height="1008" alt="Screenshot from 2025-09-21 15-14-43" src="https://github.com/user-attachments/assets/4276e60a-1681-4959-91da-63ba4b558e9b" />
<img width="1853" height="1008" alt="Screenshot from 2025-09-21 15-02-28" src="https://github.com/user-attachments/assets/0d351447-ebe0-499d-aa30-ba79e2f0a035" />
<img width="1867" height="1008" alt="Screenshot from 2025-09-21 15-17-30" src="https://github.com/user-attachments/assets/c3590ca0-d084-4fd0-95e9-d57f5877743f" />
