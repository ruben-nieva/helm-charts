# Agea Helm Charts
Internal Helm repository for packaging, versioning, and distributing enterprise Kubernetes charts.

## Manteiners
- devops@agea.com.ar

## Requirements
-  helm 3.6+

# Testing
```
helm repo add my-repo-helm https://raw.githubusercontent.com/ruben-nieva/helm-charts/refs/heads/main
helm repo update
helm search repo my-repo-helm --versions
```

## Installing adn Running this Chart

## Helm lint
```
helm lint path-to-chart
```


