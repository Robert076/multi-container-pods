# 🌎 Practicing multi-container pods

### 🚀 Useful commands:

1a. Get into a specific container:
```bash
kubectl exec -ti Pods/multi-container-pod --container nginx-container -- /bin/bash
```

1b. (same effect but shorter)
```bash
kubectl exec -ti Pods/multi-container-pod -c nginx-container -- /bin/bash
```
