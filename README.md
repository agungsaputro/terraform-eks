# Learn Terraform - Provision an EKS Cluster

This repo is a companion repo to the [Provision an EKS Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-eks-cluster), containing
Terraform configuration files to provision an EKS cluster on AWS.

## Terraform init

```
terraform init -upgrade
```


## Terraform destroy

```
terraform state rm module.eks.kubernetes_config_map.aws_auth
terraform destroy
```