# Minimal Configuration to use K8S in Github CodeSpaces.

This is the simplest way to get a simple k8s working with Codespaces, only using Microsoft pure images.

After launch Codespaces can create a new cluster and start coding:
```
$ minikube start
...
🏄  Done! kubectl is now configured to use "minikube" cluster and "default" namespace by default

$ kubectl get pods
kubectl get nodes
NAME       STATUS   ROLES           AGE   VERSION
minikube   Ready    control-plane   59s   v1.26.1
```
