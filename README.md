# multi-container-pods
Practicing multi container pods in k8s.

All the containers that are declared in the same Pod will be scheduled, or launched, on the same worker node or Docker daemon. Pods cannot span over multiple machines. All containers that are part of a pod will be launched on the same worker node!
This is something extremely important: containers in the same Pod are meant to live together. If you terminate a pod, all its containers will be killed together, and when you create a Pod, Kubelet will, at the very least, attempt to create all its containers together.
