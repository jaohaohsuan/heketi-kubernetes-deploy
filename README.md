# heketi-kubernetes-deploy

sample pvc
```
kind: "PersistentVolumeClaim"
apiVersion: "v1"
metadata:
  name: "pvc-test"
  annotations:
    volume.beta.kubernetes.io/storage-class: "default"
spec:
  accessModes:
    - "ReadWriteOnce"
  resources:
    requests:
      storage: "1Gi"
```
