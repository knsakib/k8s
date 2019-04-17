# Services
Service is like a virtual server. It has it's
own IP and port other than pod IP-Port and
node IP-Port. Service will give single interface
to combine multipele pods behind them.  

## NodePort
```
This type of services makes a port available
in the hosted node of the pod to 
communicate with the pod port. 
```

## ClusterIP
```
This type of services makes a virtual IP 
inside the cluster available to enable 
communicate between between diffrent services.   
Each Service gets assinged to a name and each
service should communicate through the name.
```

## LoadBalancer 
```
This service creates a Loadbalancer in the cloud
provider to balance the load between diffrent services.   
```

## How do we link a service to a pod
We use labels to link a service to a Pod