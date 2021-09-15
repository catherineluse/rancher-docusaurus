---
title: Installing Rancher behind an HTTP Proxy
position: 4
---

In a lot of enterprise environments, servers or VMs running on premise do not have direct Internet access, but must connect to external services through a HTTP(S) proxy for security reasons. This tutorial shows step by step how to set up a highly available Rancher installation in such an environment.

Alternatively, it is also possible to set up Rancher completely air-gapped without any Internet access. This process is described in detail in the [Rancher docs](https://rancher.com/docs/rancher/v2.6/en/installation/other-installation-methods/air-gap/).

# Installation Outline

1. [Set up infrastructure](https://rancher.com/docs/rancher/v2.6/en/installation/other-installation-methods/behind-proxy/prepare-nodes/)
2. [Set up a Kubernetes cluster](https://rancher.com/docs/rancher/v2.6/en/installation/other-installation-methods/behind-proxy/launch-kubernetes/)
3. [Install Rancher](https://rancher.com/docs/rancher/v2.6/en/installation/other-installation-methods/behind-proxy/install-rancher/)
