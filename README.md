kubectl create ns argocd
kubectl apply -f deployments/install.yaml -n argocd
kubectl apply -f deployments/ingress.yaml -n argocd
