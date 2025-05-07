# online-store-code-challenge

This repository holds all the relevant files for this "DevOps Engineer Technical Code Challenge".

## Project layout

* **README.md**
* **EXPLANATIONS.md** - why/how certain choices were made while completing the challenge

## How to run

This section shows how to run the online-store application.

### Locally

Ensure necessary tools are installed:

```bash
docker version # check also that docker daemon is running as well
minikube version
kubectl version
```

Start minikube and apply manifests: 

```bash
minikube start
kubectl apply -f aks-store-quickstart.yaml
```

Check what was deployed in default namespace or start the Kubernetes dashboard and check trough it:

```bash
kubectl get all 
minikube dashboard
```