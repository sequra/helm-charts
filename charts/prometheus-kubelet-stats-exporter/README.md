# Prometheus Kubelet Stats Exporter

Kubelet-Stats-Exporter is collect ephemeral storage information from pods allocated in kubernetes nodes.

This chart creates a [kubelet-stats-exporter](https://github.com/petros-d/kubelet-stats-exporter) deployment on kubernetes.

## Install Chart

```console
helm repo add sequra-community https://sequra.github.io/helm-charts
helm repo update
helm install [RELEASE_NAME] sequra-community/prometheus-kubelet-stats-exporter
```

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```

## Configuring

Check [values.yaml](./values.yaml) file or run:

```console
helm show values sequra-community/prometheus-kubelet-stats-exporter
```
