

## Deployment
### Deploy mysql database as deployment in Kubernetes
```
kubectl apply -f deployment/mysql/deployment/configmap.yaml
kubectl apply -f deployment/mysql/deployment/secret.yaml
kubectl apply -f deployment/mysql/deployment/deployment.yaml
kubectl apply -f deployment/mysql/deployment/service.yaml
```

### Deploy easyclaim backend java application as deployment in kubernetes
```
kubectl apply -f deployment/configmap.yaml
kubectl apply -f deployment/deployment.yaml
kubectl apply -f deployment/service.yaml
```

