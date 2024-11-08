# Self-Hosting

!!! info "Already signed up for Browsertrix?"

    This guide is for developers and users who are self-hosting Browsertrix. If you've registered through [webrecorder.net](https://webrecorder.net/browsertrix), you may be looking for the [user guide](../user-guide/index.md).

Browsertrix is designed to be a cloud-native application running in Kubernetes.

However, it is perfectly reasonable to deploy Browsertrix locally using one of the many available local Kubernetes options.

The main requirements for Browsertrix are:

- A Kubernetes Cluster
- [Helm 3](https://helm.sh/) (package manager for Kubernetes)

We have prepared a [Local Deployment Guide](local.md) which covers several options for testing Browsertrix locally on a single machine, as well as a [Production (Self-Hosted and Cloud) Deployment](remote.md) guide to help with setting up Browsertrix in different production scenarios. Information about configuring storage, crawler channels, and other details in local or production deployments is in the [Customizing Browsertrix Deployment Guide](customization.md). Information about configuring proxies to use with Browsertrix can be found in the [Configuring Proxies](proxies.md) guide.

Details on managing org export and import for existing clusters can be found in the [Org Import & Export](admin/org-import-export.md) guide.
