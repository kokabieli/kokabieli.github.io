---
title: Getting Started
weight: -20
---

This page tells you how to get started with the kokabieli, including installation and basic configuration.

<!--more-->

{{< toc >}}

## Install requirements

You need to have a running Kubernetes cluster with at least version 1.26.0.

## Install the operator

The operator can be installed with two commands:

```shell
# install the required CRDs
kubectl apply -k https://github.com/kokabieli/kokabieli-operator/config/crd

# install the operator
kubectl apply -k https://github.com/kokabieli/kokabieli-operator/config/default
```

## Install the GUI
```shell
# install the GUI
kubectl create namespace kokabieli
kubectl apply -k https://github.com/kokabieli/kokabieli-operator/config/ui -n kokabieli
```

## deploy a sample constellation
```shell
kubectl apply -k https://github.com/kokabieli/kokabieli-operator/config/default -n kokabieli
# todo: operator should be able to write configmaps in the kokabieli(-ui) namespace
```

## Access the GUI
```shell
kubectl port-forward -n kokabieli-ui service/kokabieli-ui 8080:3000
```
The GUI is now available at http://localhost:8080
