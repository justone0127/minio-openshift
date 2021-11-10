# min.io openshift template

This is a minimal [**min**io](https://min.io/) OpenShift template.

## Use

```
oc new-app -f minio-template.yaml
```

Or with access and secret keys as parameters:
```
oc new-app -f minio-template.yaml -p MINIO_ACCESS_KEY=minio -p MINIO_SECRET_KEY=minio123
```

Happy object storing!!!
