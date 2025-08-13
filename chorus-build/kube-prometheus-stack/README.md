# Kube Prometheus Stack

The Prometheus stack currently deploys:

- Prometheus;
- Alertmanager;
- and a configuration to push alerts to Webex, which needs to be enabled once the corresponding secret has been created.

## Securing the endpoints

Prometheus and Alertmanager are secured using OAuth2-Proxy.
See `prometheus-oauth2-proxy` and `alertmanager-oauth2-proxy` for more details.