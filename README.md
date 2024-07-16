# rundeck
kubectl apply -f rundeck-pvc.yaml
kubectl apply -f rundeck-deployment.yaml
kubectl apply -f rundeck-service.yaml
kubectl port-forward svc/rundeck 4440:80 -n rundeck
