# Explanations

This file provides additonal explanations, thoughts and choice I made while completing the challenge.

First step I took was to create the [repository](https://github.com/CiucurDaniel/online-store-code-challenge) with an initial README file and the explanation file (this document!). Next, I copied the [starter file](https://github.com/Azure-Samples/aks-store-demo/blob/main/aks-store-quickstart.yaml) `aks-store-quickstart.yaml` in this repository.

Next step was to see what those yamls contain and run them to see what I'm dealing with. Since the challenge requires me to show how to run the application locally using either Docker or Kubernetes I decided to chose Kubernetes and my go-to choice for a "local" Kubernetes cluster is (Minikube)[https://minikube.sigs.k8s.io/docs/].

```bash
minikube version

minikube version: v1.25.2
commit: 362d5fdc0a3dbee389b3d3f1034e8023e72bd3a7

docker version # check also is docker daemon is running

Client:
 Cloud integration: v1.0.35+desktop.10
 Version:           25.0.2
 API version:       1.44
 Go version:        go1.21.6
 Git commit:        29cf629
 Built:             Thu Feb  1 00:24:09 2024
 OS/Arch:           windows/amd64
 Context:           default
```

Confirm minkube and Docker are installed locally.