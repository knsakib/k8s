# k8s

## YAML File:
```
- Dictionary or List of Dictionaries
- To store properties of single object 
we use Dictionary/map
- If it is multiple items of the same 
type of object, we use List/Array
- By list of dictionaries, we can list
all the properties of all items.
```
-------------------
```
apiVersion:
kind: 
metadata: #Dictionary / in value position multiple non-repeted key-values
  name: myapp-pod # name and labels keys are predefined; not arbitrary; could be other
  labels: #Dictionary / in value position multiple key-values 
    app: myapp # arbitrary
spec: #Dictionary
  containers: # List / Array / multiple repeted key-values
    - name: # - indicated the first item / item starting point 
      image: 
```
## Replication Controller / Replica Set
```
Replication COntroller or ReplicaSet will make sure
that the pods are always running, even when the 
number of pods are one. Replication Controller
also helps loadbalancing among multiple pods.
Selector section will consider pods that are 
created earlier mathcing with 
spec: template: section. 
```
## Deployment
```
Deployment and ReplicaSet are same only the
difference in the objevt type.  
```