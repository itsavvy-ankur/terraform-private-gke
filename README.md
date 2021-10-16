# Terraform a private GKE Cluster using Google Cloud Modules

## Terraform Controlled Resources

* GCP project
* network and sub-network with Private Google Access turned on
* Private GKE zonal cluster ( to avoid $$$'s)

## Verification 

* https://cloud.google.com/kubernetes-engine/docs/quickstart

## Execution instructions

* Init
```sh
terraform init
```

* Plan
```sh
terraform plan -var-file=dev.tfvars
```

* Apply
```sh
terraform apply -var-file=dev.tfvars
```

* Destroy
```sh
terraform destroy -var-file=dev.tfvars
```