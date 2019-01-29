
### Create deployment
```
kubectl create -f deployment.yaml
```

### Verify deployment is created
```
kubectl get deployments
```

### Create NodePort proxy service
```
kubectl create -f service.yaml
```
