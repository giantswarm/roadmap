---
name: G8s Release
about: Template for a to-do issue to track a new g8s release
---
<!--
Please set the correct K8s version and provide a correct link to the changelog.
-->
Kubernetes XXX

https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG-XXX.md

### Provide a new release with the kubernetes version

* [ ] Check with the teams about wip changes within k8scloudconfig and the provider-specific operators. Decide with version folder to use.
* [ ] Retag new image in retagger
* [ ] Check [upstream changelogs](https://github.com/kubernetes/kubernetes/blob/master/CHANGELOG.md).
  * [ ] Check urgent upgrade notices.
  * [ ] Check deprecation notices.
  * [ ] Check component upgrades.
    * [ ] Calico
    * [ ] ETCD
    * [ ] Container Linux
* [ ] Create a PR in k8scloudconfig with the new kubernetes version
  * [ ] Update k8s version in the different template files
  * [ ] Use k8s version for `k8s-addons` (e.g. https://github.com/giantswarm/k8scloudconfig/blob/4695b7d6eb35eae234d0ce0c0c09f4b412525a68/v_4_7_0/files/conf/k8s-addons#L5)
* [ ] Update cluster-autoscaler
* [ ] Vendor k8scloudconfig in the provider-specific operators
* [ ] Create a wip release (major version change if it is a minor kubernetes upgrade)
* [ ] Do this for each provider
* [ ] Check Prometheus rules for deprecated metrics and fix them if necessary

### Check migration recommendations

Check migration recommendations from kubernetes and decide what we need to document for the customer and what we should migrate automatically for them

* [ ] Do we need to change our own resources within the tenant clusters?
* [ ] What do we need to communicate to our customers?
* [ ] Anything else that would be better automated for the upgrade?

### Run e2e and conformance tests

* [ ] Start a new cluster and run conformance tests against it
* [ ] Start a new cluster and run e2e tests against it
* [ ] Do this for each provider

### Check Core Components

* [ ] Check core components for updates and include them in cluster-operator
  * [ ] Cert-exporter
  * [ ] Chart-operator
  * [ ] Cluster-autoscaler
  * [ ] CoreDNS
  * [ ] Kube-state-metrics
  * [ ] Net-exporter
  * [ ] Nginx ingress controller
  * [ ] Node-exporter
* [ ] All helm releases in the giantswarm namespace should be in status deployed
* [ ] Core components are runnning without errors
  * [ ] Cert-exporter
  * [ ] Chart-operator
  * [ ] Cluster-autoscaler
  * [ ] CoreDNS
  * [ ] Kube-state-metrics
  * [ ] Net-exporter
  * [ ] Nginx ingress controller
  * [ ] Node-exporter
* [ ] Cluster-operator is running without errors
* [ ] Cluster-operator is able to create chart-configs in the tenant

### Test migration (both cluster functionality itself and workloads)

* [ ] Start a cluster with an older version and upgrade the cluster to the new release
* [ ] Upgrade a cluster that is not critical but has some more real workloads (eg giantswarm website, dev cluster of customer)
* [ ] Do this for each provider

### Write summary for the release and update docs

* [ ] Write some release notes
* [ ] Check if our docs need to be updated
* [ ] Announce the release internally (SEs are important here)
* [ ] Announce the release to the customers
