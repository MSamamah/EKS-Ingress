# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name <cluster name> --region <rigion> --fargate
```

## Delete the cluster

```
eksctl delete cluster --name <cluster name> --region <rigion>
```



