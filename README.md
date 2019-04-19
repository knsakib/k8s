## Sample Application Local Kubernetes 

```
Not usre if this yaml implementation works or not.
Git: https://github.com/kubernetes/examples/tree/master/guestbook
Docker hub: https://hub.docker.com/r/kubernetes/guestbook
Instruction???: https://github.com/kubernetes/examples/blob/master/guestbook-go/README.md
```

### guestbook-app Deployment Creation
```
kubectl create -f guestbook-app-Deployment.yaml
kubectl get Deployments
```

### guestbook-app Service Creation
```
kubectl create -f guestbook-app-service.yaml
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