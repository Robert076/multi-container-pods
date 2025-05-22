# 🌎 Practicing multi-container pods

### 🚀 Useful commands:

1. Get into a specific container:
```bash
kubectl exec -ti Pods/multi-container-pod --container nginx-container -- /bin/bash
              |
              |
             / \
            /   \
  -t simulates   -i keeps the stdin connection open
  a terminal        so that you can run commands into it
```
