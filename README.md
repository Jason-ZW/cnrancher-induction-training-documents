# Induction Training Documents

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/Jason-ZW/cnrancher-induction-training-documents/pulls)
[![GitHub release](https://img.shields.io/github/release/Jason-ZW/cnrancher-induction-training-documents.svg)](https://github.com/Jason-ZW/cnrancher-induction-training-documents/releases)
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

This repository contains a variety of essential rancher skills and can be used as a starter guide for developers to help them master the farm-related technology patterns in a short period of time.
If you want to know how to develop rancher related components and products, please read on.

- UI&UE - please refer [here](UI&UE/README.md).
- Q&A - please refer [here](Q&A/README.md).
- Company's Account Application - please refer [here](ACCOUNT.md).

## Before you begin

You need to know about rancher & cnrancher companies's products & projects. You can learn more about from [rancher's](https://www.rancher.com) website or [cnrancher's](https://www.rancher.cn) website.

**Products:**
- [rancher](https://github.com/rancher/rancher) - Rancher is an open source project that provides a container management platform built for organizations that deploy containers in production. Rancher makes it easy to run Kubernetes everywhere, meet IT requirements, and empower DevOps teams.
- [rancheros](https://github.com/rancher/os) - The smallest, easiest way to run Docker in production at scale. Everything in RancherOS is a container managed by Docker.
- [rke](https://github.com/rancher/rke) - Rancher Kubernetes Engine, an extremely simple, lightning fast Kubernetes installer that works everywhere.

**Projects:**
- [k3s](https://github.com/rancher/k3s) - Lightweight Kubernetes. Easy to install, half the memory, all in a binary less than 40mb.
- [longhorn](https://github.com/longhorn/longhorn) - Longhorn is a distributed block storage system for Kubernetes.
- [rio](https://github.com/rancher/rio) - Rio is a MicroPaaS that can be layered on top of any standard Kubernetes cluster.
- [k3os](https://github.com/rancher/k3os) - K3OS is a Linux distribution designed to remove as much as possible OS maintenance in a Kubernetes cluster. It is specifically designed to only have what is need to run k3s.
- [submariner](https://github.com/submariner-io/submariner) - Submariner is a tool built to connect overlay networks of different Kubernetes clusters.

## Development Workflow

If you want to perform a functional commit against a repository, `fork` the repository first. After that please `modify` and `test` the code in the repository which you `forked` before. If everything is ok, please submit a `Pull Request` to the `upstream` repository and `assign a reviewer`. Then wait the `Pull Request` be merged.

Self-testing is an important step. Make sure your code is self-tested before submitting a `Pull Request`.

## Basic skills

Good Golang programming ability and Linux related basic operation and maintenance ability are the basic requirements.

**Frameworks & Utilities:**
- [rancher/dapper](https://github.com/rancher/dapper) - Dapper is a tool to wrap any existing build tool in an consistent environment. This allows people to build your software from source or modify it without worrying about setting up a build environment.
- [rancher/go-skel](https://github.com/rancher/go-skel) - Skeleton for Rancher Go Microservices.
- [gnu/make](https://www.cl.cam.ac.uk/teaching/0910/UnixTools/make.pdf) - The make utility automatically determines which pieces of a large program need to be recompiled, and issues commands to recompile them.

## Let's begin

We will set aside 2 weeks for you to finish the following contents. Please keep your demo environment for our inspection.

You also need to be familiar with the company's work environment. Before that, you need to improve and provide personal information so that we can quickly open the relevant account, refer [here](ACCOUNT.md).

**Company's Work Environment**
- Complete the configuration of Slack/Email/Zoom/Office and other working software. (office software can be downloaded through office.com).
- Complete the configuration of Github account, join RancherLabs(rancher or cnrancher) organizations, and be familiar with the basic use of Github.
- Familiar with the preparation, submission, and modification process of relevant weekly reports.
- Familiar with relevant weekly report preparation, submission, modification process.
  - Shenyang - https://github.com/cnrancher/sy-teamblog

**Docker Related**

1. Build a docker image using Dockerfile.
2. Build a docker image using Dockerfile with multi-stage features.
3. Run a containerized service with a docker-compose and use the host network.
4. Complete network communication between two containers via veth-paris & network namespaces.

**Kubernetes Related**

1. Use RKE deploy a Kubernetes cluster (1 master and 2 nodes).
2. Run a WordPress application in Kubernetes and expose the service using ingress.
3. Add a dynamic NFS provisioner to your Kubernetes cluster, run an application using NFS storage.
4. Use [kubernetes/client-go](https://github.com/kubernetes/client-go) to CRUD Kubernetes Deployment.
5. Extend the Kubernetes API with CustomResourceDefinitions.
6. Refer to [kubernetes/sample-controller](https://github.com/kubernetes/sample-controller) write a controller watch CRD resource and print the logs.
7. Refer to [kubernetes-sigs/kubebuilder](https://github.com/kubernetes-sigs/kubebuilder) write a controller watch CRD resource and print the logs.

**Rancher Related**

1. Rancher single node install.
2. Rancher high availability (HA) install.
3. Deploy an application from Rancher AppCatalog, use NodePort expose the application.
4. Backing up and Restore etcd from rancher ui.

## References documents

- [awesome/rancher](https://github.com/jmreicha/awesome-rancher)
- [makefile/tutorial](https://makefiletutorial.com/)

# License

Copyright (c) 2014-2019 [Rancher Labs, Inc.](http://rancher.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
