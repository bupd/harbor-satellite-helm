# Helm Chart for Harbor Satellite

## Introduction

This [Helm](https://github.com/kubernetes/helm) chart installs [Harbor](https://github.com/container-registry/harbor-satellite) in a Kubernetes cluster. Welcome to [contribute](CONTRIBUTING.md) to Helm Chart for Harbor.

## Prerequisites

- Kubernetes cluster 1.20+
- Helm v3.2.0+

## Installation

### Add Helm repository
TBD
<!---->
<!-- ```bash -->
<!-- helm repo add harbor https://helm.goharbor.io -->
<!-- ``` -->

### Configure the chart
TBD

The following items can be set via `--set` flag during installation or configured by editing the `values.yaml` directly (need to download the chart first).

### Install the chart

Install the Harbor Satellite helm chart with a release name `my-release`:
```bash
helm install my-release harbor/harbor-satellite
```

## Uninstallation

To uninstall/delete the `my-release` deployment:
```bash
helm uninstall my-release
```

## Configuration
TBD
<!---->
<!-- The following table lists the configurable parameters of the Harbor chart and the default values. -->
