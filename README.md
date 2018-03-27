k8default Dployment files
========================

TODO: Create helm chart for deployments

Kubectl Commands
==============
Create/Update Deployment and service definitions
------
```
kubectl apply -f /capture_order_api/deploy.yaml
kubectl apply -f /capture_order_api/service.yaml

kubectl apply -f /eventlistner/deploy.yaml

kubectl apply -f /fulfill_order_api/deploy.yaml
kubectl apply -f /fulfill_order_api/service.yaml
```

Delete definitions
----
```
kubectl delete -f /capture_order_api/deploy.yaml
kubectl delete -f /capture_order_api/service.yaml

kubectl delete -f /eventlistner/deploy.yaml

kubectl delete -f /fulfill_order_api/deploy.yaml
kubectl delete -f /fulfill_order_api/service.yaml
```