# helm-charts
helm charts for multiple backbone projects

## Install Istio
```
helm dependency build
helm install -n istio-system --create-namespace istio-base ./
kubectl label namespace default istio-injection-
```