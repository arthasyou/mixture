# keubctl

### get
<!-- Code Blocks --->
```
 kubectl get [type] <name> -n <namespace_name>
```

### deployment
<!-- Code Blocks --->
```
 kubectl create deployment <deploy_name> --image=<docker_image_name:version>
```

### edit deployment
<!-- Code Blocks --->
```
 kubectl edit deployment <deploy_name>
```

### delete deployment
<!-- Code Blocks --->
```
 kubectl delete deployment <deploy_name>
```

### describe pod
<!-- Code Blocks --->
```
 kubectl describe pod <pod_name>
```

### exec pod
<!-- Code Blocks --->
```
 kubectl exec -it <pod_name> -- [cmd]
```

### apply file
<!-- Code Blocks --->
```
 kubectl apply -f <config-file.yml> --namespace=[namespace_name]
```

<!-- [link](https://google.com) -->
