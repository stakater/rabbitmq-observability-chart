# rabbitmq-observability-chart
A helm chart which contains RabbitMQ alerting rules, Alertmanager configuration and RabbitMQ dashboards

Pre-Reqs: Prometheus, Alertmanager and Grafana should be installed in the cluster before applying the chart

To install the chart with the release name rabbitmq-observability in namespace test:

```yaml
helm repo add stakater https://stakater.github.io/stakater-charts
helm repo update
helm install rabbitmq-observability stakater/rabbitmq-observability --namespace test
```