# Kubernetes Cheat Sheet #

## Kubectl config

To use kubectl you must first update it's configuration file which live in .kube folder of your home directory (~/.kube/config). This will tell it to which k8s cluster to connect to.

When you enable Kubernetes in docker-desktop, it will update the config automatically.

Tell Kubernetes to use the docker configuration:
```
kubectl config use-context docker-desktop
```
Verify that the Kubernetes clustes it working:
```
kubectl get nodes
```
