# Select namespace by label with label selector

```
kind create cluster
kubectl label namespace default foo=bar
go run select-namespaces-with-label-selectors.go foo=bar
```
