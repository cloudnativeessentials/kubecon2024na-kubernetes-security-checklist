# Stop Kubernetes' Revolving Door: A Hands-On Tutorial to Secure a Kubernetes Cluster

## Install kind on RHEL

The install-kind-cilium.sh script installs Docker, jq, kind, kubectl, Cilium and creates a kind cluster (1 control plane, 2 worker nodes) on RHEL

To run the script, run the following:

```shell
curl https://raw.githubusercontent.com/cloudnativeessentials/101-kubernetes-security/main/install-kind-cilium.sh | sh
```
