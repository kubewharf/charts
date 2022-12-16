# Malachite Helm Charts

## TL;DR

```
helm repo add kubewharf https://kubewharf.github.io/charts
helm repo update

helm install malachite -n malachite-system --create-namespace kubewharf/malachite
```