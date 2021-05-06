# Kubestriker Helm Chart

This repository contains the official Kubestriker Helm chart for installing
and configuring Kubestriker on Kubernetes. 

## Prerequisites
  * **Helm 3.0+** (Helm 2 is not supported)
  * **Kubernetes 1.13+** - This is the earliest version of Kubernetes tested.
    It is possible that this chart works with earlier versions but it is
    untested.

## Usage

1. Clone this repository and navigate to kubestriker-helm folder.

2. Now you're ready to install Kubestriker! To install using Helm 3 run:
        $ helm install kubestiker ./kubestriker

3. For testing the output of the files. run:
        $ helm install --dry-run kubestiker ./kubestriker > ./kubestriker/test.txt

