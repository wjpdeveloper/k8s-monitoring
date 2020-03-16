# k8s-monitoring
build up a monitoring system using grafana, alertmanager, prometheus on k8s.



Below **variables** need to be replaced with real value. 

| Var                       | Desc                               |
| --------                  | --------                           |
| `${webhookUrl}`           | alert receiver's webhook url.      |
| `${grafanaDomain}`        | domain of grafana to visit         |
| `${prometheusDomain}`     | domain of prometheus to visit      |
| `${alertmanagerDomain}`   | domain of alertmanager to visit    |
| `${adminUser}`            | grafana admin username             |
| `${adminPasswd}`          | grafana admin password             |
| `${grafanaPlugins}`          | grafana plugins to add             |

storage used **cinder-ssd**, you can use any other provisioners, list at https://kubernetes.io/docs/concepts/storage/storage-classes/.

#### Monitoring SpringBoot App
reference: https://micrometer.io/

#### Monitoring MongoDB
reference: https://devconnected.com/mongodb-monitoring-with-grafana-prometheus/

#### Monitoring Redis
reference: https://github.com/oliver006/redis_exporter

