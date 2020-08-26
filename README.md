# kubernetes-configmap-reload
ConfigMap reload example

### You can deploy the application using:

```bash
oc new-app redhat-openjdk18-openshift:1.4~https://github.com/jovemfelix/kubernetes-configmap-reload.git \
    --name=minikube-sample \
    -lapp=minikube-sample
```



## Reference

- Step-by-step: https://medium.com/swlh/kubernetes-configmap-confuguration-and-reload-strategy-9f8a286f3a44
- Official documentation: https://cloud.spring.io/spring-cloud-kubernetes/reference/html/#propertysource-reload