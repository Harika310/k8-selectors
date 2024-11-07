# Selectors

Taint the node
```
kubectl taint nodes ip-192-168-10-8.ec2.internal   hardware=gpu:NoSchedule

label the node

```
kubectl label nodes ip-192-168-10-8.ec2.internal hardware=gpu

```
Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes
