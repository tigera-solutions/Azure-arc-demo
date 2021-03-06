# Calicocloud configuration sample for Azure Arc enabled Kubernetes 

This repository contains sample Kubernetes manifest files for calico networkpolicy that can be deployed using GitOps to an Azure Arc enabled Kubernetes cluster.

## Contents

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `README.md`       | This README file. |
| `cluster-apps`    | Contains an example application that should be deployed to every cluster. |
| `namespaces`    | Contains namespace resources to provision on an attached cluster. |
| `cluster-networkpolicy`    | Contains an example networkpolicy that should be deployed to every cluster. |


## Prerequisites

One or more Kubernetes clusters are [connected to Azure Arc](https://docs.microsoft.com/en-in/azure/azure-arc/kubernetes/connect-cluster) using the `connectedk8s` Azure CLI extension.



## Contributing

Before contributing code, please see the [CONTRIBUTING](CONTRIBUTING.md) guide.

Issues, PRs and Feature Request have their own templates. Please fill out the whole template.