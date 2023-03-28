# pod-envs

Print envs for specific container inside the particular pod. Extract needed data from secrets, configmaps, fieldRef and resourceFieldRef.

Usage:
```
Usage of pod-envs:
  -c, --container string   Container inside that pod from which to extract envs. Unused if there's only 1 container
  -h, --help               print help msg
      --name string        namespace of the pod
      --namespace string   namespace of the pod (default "default")
  -p, --pretty             pretty print output if json
  -y, --yaml               switch from json to yaml output
```