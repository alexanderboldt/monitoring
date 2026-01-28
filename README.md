# :bar_chart: Monitoring

This project displays database- and system-metrics from various projects with Grafana and Prometheus.

## :whale: Install with Docker
Create and start the containers:
```bash
docker compose up -d
```

## :wheel: Install with Kubernetes
Install all objects with Kustomize:
```bash
kubectl kube apply -k kustomize/base
```

Delete the project namespace and the objects if not needed anymore:
```bash
kubectl delete namespace monitoring
```
