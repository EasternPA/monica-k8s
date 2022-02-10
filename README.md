# monica-k8s
files for managing monicahq in k8s with argocd

```
kubectl apply -f monicahq-ns.yaml
kubens monicahq
kubectl apply -f monicadb-env.yaml
kubectl apply -f monica-env.yaml
kubectl apply -f db-deploy.yaml
kubectl apply -f db-svc.yaml
kubectl apply -f monica-deploy.yaml
kubectl apply -f app-svc.yaml
```
