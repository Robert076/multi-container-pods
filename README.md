# 🌎 Practicing multi-container pods

### 🚀 Useful commands:

---

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

You can use an alternative for quickly running just one command like `ls`:
```bash
kubectl exec pods/multi-container-pod -c nginx-container -- ls
```

---
