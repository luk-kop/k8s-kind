# k8s-kind

## Requirements
- kind v0.23.0


- The `kind-config.yaml` file is configured for Kubernetes **1.29** version. You can find available image tags for the node's container on the [kind releases page](https://github.com/kubernetes-sigs/kind/releases).
- Cluster configuration:
    - 1 x master node
    - 2 x worker nodes

Example commands:

```bash
kind create cluster --config kind-config.yaml
```