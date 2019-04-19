## Sample Application Local Kubernetes 

### voting-app Deployment Creation
```
kubectl create -f voting-app-Deployment.yaml
kubectl get Deployments
```

### voting-app Service Creation
```
kubectl create -f voting-app-service.yaml
kubectl get services 
```

### redis Deployment Creation
```
kubectl create -f redis-Deployment.yaml
kubectl get Deployments
```

### redis Service Creation
```
kubectl create -f redis-service.yaml
kubectl get services 
```

### postgres Deployment Creation
```
kubectl create -f postgres-Deployment.yaml
kubectl get Deployments
```

### postgres Service Creation
```
kubectl create -f postgres-service.yaml
kubectl get services
```

### worker-app Deployment Creation
```
kubectl create -f worker-app-Deployment.yaml
kubectl get Deployments
```

### result-app Deployment Creation
```
kubectl create -f result-app-Deployment.yaml
kubectl get Deployments
```

### result-app Service Creation
```
kubectl create -f result-app-service.yaml
kubectl get services
```