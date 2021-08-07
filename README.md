# fictional-fortnight

run:
kubectl apply -f manifest/
kubectl port-forward --namespace=kubedoom $(PODNAME) 5900:5900

connect vnc ip:5900