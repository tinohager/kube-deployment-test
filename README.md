```
kubectl apply -f https://raw.githubusercontent.com/tinohager/kube-deployment-test/main/deployment.yaml
kubectl get deployments
kubectl apply -f https://raw.githubusercontent.com/tinohager/kube-deployment-test/main/service.yaml
kubectl get services
```

```
kubectl delete svc nager-date
kubectl delete deploy nager-date
```
