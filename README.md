

![Kong](images/kong_way.png)
# Overview
Deploy the Kong API Gateway along with the Admin API to Kubernetes

## Deploying Resources
```bash
> $ kubectl create -f kong_dbless.yaml
``

## Modify Resources
```bash
> $ kubectl apply -f kong_dbless.yaml
``

## Deleting Resources
```bash
> $ kubectl delete -f kong_dbless.yaml
``