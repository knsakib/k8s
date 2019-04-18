## Sample Application Local Kubernetes 

### voting-app Pod Creation
```
kubectl create -f voting-app-pod.yaml
kubectl get pods
```

### voting-app Service Creation
```
kubectl create -f voting-app-service.yaml
kubectl get services 
```

### redis Pod Creation
```
kubectl create -f redis-pod.yaml
kubectl get pods
```

### redis Service Creation
```
kubectl create -f redis-service.yaml
kubectl get services 
```

### postgres Pod Creation
```
kubectl create -f postgres-pod.yaml
kubectl get pods
```

### postgres Service Creation
```
kubectl create -f postgres-service.yaml
kubectl get services
```

### worker-app Pod Creation
```
kubectl create -f postgres-pod.yaml
kubectl get pods
```

### worker-app Pod Creation
```
kubectl create -f postgres-pod.yaml
kubectl get pods
```