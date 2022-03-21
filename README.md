# Create VSI on IBM Cloud

This terraform script create a vsi on IBM Cloud using terraform.


## 1. Pre-requisites

1. Install terraform on your machine (this script was tested with terraform v 1.1.7)
2. Place your ibm-api-key in terraform.tfvars file
3. Create an ssh key on your machine and create a 'ssh key' on IBM Cloud using the public key. The name of this key is required to be input during 'plan' and 'apply' phases of terrform commands.

## 2. Create VSI

Run terraform commands:

```
terraform init
```

```
terraform plan
```

```
terraform apply
```

Check the virtual server instance ready in your account in a couple of minutes.
