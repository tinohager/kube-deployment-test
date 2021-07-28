```
kubectl apply -f https://raw.githubusercontent.com/tinohager/kube-deployment-test/main/deployment.yaml
kubectl get deployments
kubectl expose deployment nager-date --type=LoadBalancer
kubectl get services
```

```
kubectl delete svc nager-date
kubectl delete deploy nager-date
```
