# 🌎 Practicing multi-container pods

### 🚀 Useful commands:

1. Get into a specific container:
```bash
kubectl exec -ti Pods/multi-container-pod --container nginx-container -- /bin/bash
```

or a shorter version:
```bash
kubectl exec -ti Pods/multi-container-pod -c nginx-container -- /bin/bash
```
