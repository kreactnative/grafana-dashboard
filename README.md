# grafana-dashboard

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update prometheus-community
git clone https://github.com/kreactnative/grafana-dashboard.git
cd grafana-dashboard
git checkout nt-dev-qa
helm upgrade --install kube-prometheus-stack  --create-namespace  --namespace monitoring  prometheus-community/kube-prometheus-stack -f prometheus-stack-values.yaml --wait
```
