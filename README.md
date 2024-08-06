# Description

Add the following lines in your settings.json file:

```json
{
  "yaml.schemas": {
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/alertmanager.monitoring.coreos.com.json": ["*alertmanager.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/alertmanagerconfig.monitoring.coreos.com.json": ["*alertmanagerconfig.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/podmonitor.monitoring.coreos.com.json": ["*podmonitor.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/probe.monitoring.coreos.com.json": ["*probe.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/prometheus.monitoring.coreos.com.json": ["*prometheus.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/prometheusagent.monitoring.coreos.com.json": ["*prometheusagent.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/prometheusrule.monitoring.coreos.com.json": ["*prometheusrule.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/scrapeconfig.monitoring.coreos.com.json": ["*scrapeconfig.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/servicemonitor.monitoring.coreos.com.json": ["*servicemonitor.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/thanosruler.monitoring.coreos.com.json": ["*thanosruler.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/application.argoproj.io.v1alpha1.json": ["*application*.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/appproject.argoproj.io.v1alpha1.json": ["*appproject*.yaml"],
    "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/applicationset.argoproj.io.v1alpha1.json": ["*applicationset*.yaml"]
  }
}
```
