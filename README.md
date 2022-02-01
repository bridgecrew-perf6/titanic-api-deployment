# Titanic API Deploment 

## Purpose

The purpose of this is repository is for training the next generation of Cloud Native experts.

This serves as the home to the deployments related to the [titanic-api](https://github.com/chris-cmsoft/titanic-api) deployed on the [titanic-api-infrastructure](https://github.com/chris-cmsoft/titanic-api-infrastructure)

## Prerequisites

* [Kustomize](https://kustomize.io/)

## Installation

In order to install the titanic-api you'll need to apply the Kubernetes manifests

```bash
kustomize build . | kubectl apply -f -
```
