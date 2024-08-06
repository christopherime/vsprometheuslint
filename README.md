# Description

Add the following lines in your settings.json file:

```json
"yaml.schemas": {
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/alertmanager.monitoring.coreos.com.json": ["*alertmanager.y*ml","*/alertmanager/**/*.y*ml","*/alertmanagers/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/alertmanagerconfig.monitoring.coreos.com.json": ["*alertmanagerconfig.y*ml","*/alertmanagerconfig*/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/podmonitor.monitoring.coreos.com.json": ["*podmonitor.y*ml","*/podmonitor*/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/probe.monitoring.coreos.com.json": ["*probe.y*ml","*/probe*/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/prometheus.monitoring.coreos.com.json": ["*prometheus.y*ml","*/prometheus/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/prometheusagent.monitoring.coreos.com.json": ["*prometheusagent.y*ml","*/prometheusagent*/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/prometheusrule.monitoring.coreos.com.json": ["*prometheusrule.y*ml", "rules/*.y*ml","*/prometheusrule*/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/scrapeconfig.monitoring.coreos.com.json": ["*scrapeconfig.y*ml","*/scrapeconfig*/**/*.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/servicemonitor.monitoring.coreos.com.json": ["*servicemonitor.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/thanosruler.monitoring.coreos.com.json": ["*thanosruler.y*ml"],
  "https://raw.githubusercontent.com/geekxflood/vsprometheuslint/main/applicationset.argoproj.io.v1alpha1.json": ["*/applicationSets/**/*.y*ml"]
},
```
