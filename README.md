# kubernetes_cluster

kubectl create deployment nginx-app --image=nginx --replicas=2
kubectl expose deployment nginx-app --type=NodePort --port=80
kubectl get svc nginx-app
kubectl describe svc nginx-app
