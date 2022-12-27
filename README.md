## Install

Nginx ingress controller
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.5.1/deploy/static/provider/cloud/deploy.yaml
```

cert-manager.io
```
kubectl apply --validate=false -f https://github.com/cert-manager/cert-manager/releases/download/v0.14.3/cert-manager.crds.yaml
```
