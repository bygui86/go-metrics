
# Go exporting metrics sample project

## Notice

Here we use `promauto` module instead of normal `prometheus` one, so we can avoid to manually register the Prometheus collector with kind of following command

```
prometheus.MustRegister(myCustomMetric)
```

---

## Versions

### version 0.0.1
- [x] simple rest apis
- [x] default metrics

### version 0.0.2
- [x] multistage dockerfile
- [x] kubernetes manifests

### version 0.0.3
- [x] custom metrics

---

## Links
* https://prometheus.io/docs/guides/go-application/
* https://scot.coffee/2018/12/monitoring-go-applications-with-prometheus/
* https://levelup.gitconnected.com/multi-stage-docker-builds-with-go-modules-df23b7f91a67
