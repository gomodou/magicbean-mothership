# magicbean-mothership


start:

```
kubectl apply -f .         
```
 
stop:

```
kubectl delete -f .
```

logs:

```
kubectl get pods
kubectl logs --tail=-1 backend-595c68f6d-t57rs 
```

inspect:

```
kubectl exec -it ngx-pod -- sh
```

service:

```
kubectl get svc  
```
