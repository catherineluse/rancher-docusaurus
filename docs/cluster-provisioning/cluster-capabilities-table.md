---
headless: true
---


| Action | Rancher Launched Kubernetes Clusters |  EKS, GKE and AKS Clusters\<sup\>1\</sup\> | Other Hosted Kubernetes Clusters | Non-EKS or GKE Registered Clusters |
| --- | --- | ---| ---|----|
| [Using kubectl and a kubeconfig file to Access a Cluster](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/cluster-access/kubectl/) | ✓ | ✓ | ✓ | ✓ |
| [Managing Cluster Members](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/cluster-access/cluster-members/) | ✓ | ✓ | ✓ | ✓ |
| [Editing and Upgrading Clusters](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/editing-clusters/) | ✓ | ✓ | ✓ | ✓\<sup\>2\</sup\> |
| [Managing Nodes](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/nodes) | ✓ | ✓ | ✓ | ✓\<sup\>3\</sup\> |
| [Managing Persistent Volumes and Storage Classes](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/volumes-and-storage/) | ✓ | ✓ | ✓ | ✓ |
| [Managing Projects, Namespaces and Workloads](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/projects-and-namespaces/) | ✓ | ✓ | ✓ | ✓ |
| [Using App Catalogs](https://rancher.com/docs/rancher/v2.6/en/helm-charts/) | ✓ | ✓ | ✓ | ✓ |
| Configuring Tools (Alerts, Notifiers, Logging, Monitoring, Istio) | ✓ | ✓ | ✓ | ✓ |
| [Running Security Scans](https://rancher.com/docs/rancher/v2.6/en/security/security-scan/) | ✓ | ✓ | ✓ | ✓ |
| [Use existing configuration to create additional clusters](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/cloning-clusters/)| ✓ | ✓ | ✓ | |
| [Ability to rotate certificates](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/certificate-rotation/) | ✓ | ✓  |  | |
| [Ability to [backup](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/backing-up-etcd/) and [restore](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/restoring-etcd/) Rancher-launched clusters | ✓ | ✓ |  | ✓\<sup\>4\</sup\> |
| [Cleaning Kubernetes components when clusters are no longer reachable from Rancher](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/cleaning-cluster-nodes/) | ✓ | | | |
| [Configuring Pod Security Policies](https://rancher.com/docs/rancher/v2.6/en/cluster-admin/pod-security-policy/) | ✓ | ✓ |  ||

1. Registered GKE and EKS clusters have the same options available as GKE and EKS clusters created from the Rancher UI. The  difference is that when a registered cluster is deleted from the Rancher UI, it is not destroyed.

2. Cluster configuration options can't be edited for registered clusters, except for [K3s and RKE2 clusters.](https://rancher.com/docs/rancher/v2.6/en/cluster-provisioning/registered-clusters/)

3. For registered cluster nodes, the Rancher UI exposes the ability to cordon, drain, and edit the node.

4. For registered clusters using etcd as a control plane, snapshots must be taken manually outside of the Rancher UI to use for backup and recovery.
