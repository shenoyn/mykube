How to run:
kubectl apply -f service.yaml

NOTE:
If using minikube, the deployments and the pods run inside a VM
To access the same from your laptop, you need to perform port forwarding

eg: kubectl port-forward deployment/sample-deploy 7000:80
