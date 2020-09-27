# initContainers

This creates a simple Kubernetes Deployment that has 2 Init containers.

1) First Init container will pull a test index.html page and mount it in an emptydir
2) Second Init container checks that there is an myservice service running

2nd YAML file creates the myservice clusterIP service 

All Deployments and services are created in test namespace (which must exist)
