---
title: 'Release Notes'
taxonomy:
    tag:
        - metakube
        - release-notes
---
## 2018-10-08

* Updated the backup utility [ark](https://github.com/heptio/ark) to 0.9.7

## 2018-10-04

* Kubernetes versions 1.9.11 and 1.10.8 are now available
* Updated the backup utility [ark](https://github.com/heptio/ark) to 0.9.6

## 2018-09-27

* Clusters now come with [Helm](https://www.helm.sh/) already installed and configured. See also [Using Helm](../../03.Tutorials/17.using-helm/default.en.md).

## 2018-09-18

* Updated the backup utility [ark](https://github.com/heptio/ark) to 0.9.5 which fixes the restic integration ([Release Notes](https://github.com/heptio/ark/releases/tag/v0.9.5))

## 2018-09-14

* MetaKube is now a [Certified Hosted Kubernetes Platform](https://landscape.cncf.io/landscape=certified-kubernetes-hosted&selected=sys-eleven-meta-kube). The conformance test results are publicly available for Kubernetes [1.10](https://github.com/cncf/k8s-conformance/tree/master/v1.10/metakube) and [1.11](https://github.com/cncf/k8s-conformance/tree/master/v1.11/metakube)

## 2018-09-13

* Kubernetes versions 1.10.7 and 1.11.3 are now available

## 2018-09-12

* [kubernetes-dashboard](../../02.Documentation/04.kubernetes-dashboard/default.en.md) is updated to version 1.10.0 ([Release Notes](https://github.com/kubernetes/dashboard/releases/tag/v1.10.0))

## 2018-09-05

* The `default` namespace now comes with a [LimitRange](https://kubernetes.io/docs/tasks/administer-cluster/manage-resources/memory-default-namespace/)
  that assigns a default CPU and memory request to pods that do not define one explicitly. See also [LimitRange](../../02.Documentation/07.kubernetes-limitrange/default.en.md).

## 2018-08-22

* Kubernetes version 1.11.1 and 1.11.2 are now available
* Clusters now come with managed cross-region cluster backup solution, see [Backups](../../02.Documentation/06.backups/default.en.md)
* Security groups in [LoadBalancer services](../../03.Tutorials/13.create-a-load-balancer/default.en.md) are managed automatically
* Clusters now come with managed metrics-server which enables [Horizontal Pod AutoScaling](../../03.Tutorials/19.use-horizontal-pod-autoscaling/default.en.md)
* Cluster creation: Drop-downs instead of free-text input boxes to choose from available floating IP pools, security groups, networks and subnets

## 2018-08-08

* Kubernetes versions 1.10.6 and 1.9.10 are now available

## 2018-08-01

* MetaKube is now generally available
