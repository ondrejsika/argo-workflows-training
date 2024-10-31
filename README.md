# argo-workflows-training

## Install Argo Workflows to Kubernetes

https://argo-workflows.readthedocs.io/en/latest/installation/

```bash
kubectl create namespace argo
kubectl apply -n argo -f https://github.com/argoproj/argo-workflows/releases/download/v3.5.12/quick-start-minimal.yaml
```

## Install Argo Workflows CLI

https://github.com/argoproj/argo-workflows/releases/

TODO

## Argo Workflows Dashboard

```bash
kubectl -n argo port-forward svc/argo-server 2746:2746
```

See: http://127.0.0.1:2746
