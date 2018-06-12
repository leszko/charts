# Hazelcast

[Hazelcast](http://hazelcast.com/) is an operational, in-memory, distributed, computing platform for managing data and performing parallel execution for application speed and scale.


## Quick Start

```bash
$ helm install stable/hazelcast
```

## Introduction

This chart bootstraps a [Hazelcast](https://github.com/hazelcast/hazelcast-docker/tree/master/hazelcast-kubernetes) deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Prerequisites

- Kubernetes 1.8+

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install --name my-release stable/hazelcast
```

The command deploys Hazelcast on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```bash
$ helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

The following table lists the configurable parameters of the Hazelcast chart and their default values.

| Parameter                                  | Description                                                                                                    | Default                              |
|--------------------------------------------|----------------------------------------------------------------------------------------------------------------|--------------------------------------|
| `image`                           | Hazelcast Image registry                                                                                           | `docker.io`                                          |