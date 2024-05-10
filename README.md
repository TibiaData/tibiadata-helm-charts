# TibiaData Helm Charts

[![Release Status](https://github.com/TibiaData/tibiadata-helm-charts/actions/workflows/release.yaml/badge.svg?branch=main)](https://github.com/TibiaData/tibiadata-helm-charts/actions)
[![GitHub license](https://img.shields.io/github/license/TibiaData/tibiadata-helm-charts)](https://github.com/TibiaData/tibiadata-helm-charts/blob/main/LICENSE)

TibiaData Helm charts for deploying into Kubernetes.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repository as follows:

```console
helm repo add tibiadata https://charts.tibiadata.com
helm repo update
```

You can then run `helm search repo tibiadata` to see the charts.
