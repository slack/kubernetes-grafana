Service and ReplicationController manifests for running grafana standalone.

```console
    $ kubectl create -f grafana-svc.yaml
    $ kubectl create -f grafana-rc.yaml
```

Service is available on `SVC_IP:3000`
