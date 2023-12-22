## Kubeshark Operator for Openshift.

### Prerequisites

- Access to Openshift Cluster.
- Login as `cluster-admin`


Apply Kubeshark CRD

```
oc apply -f config/crd/bases/apps.kubeshark.co_kubesharks.yaml
```

then

```
make run
```

