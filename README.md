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

`-t` is for simulating a *terminal* <br>
`-i` keeps the *stdin* connection open so you can actively write commands

You can avoid these if you just want to run a quick command like `ls`:
```bash
kubectl exec pods/multi-container-ood -c nginx-container -- ls
```
