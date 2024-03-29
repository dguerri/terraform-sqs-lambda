# Simple terraform IaC for AWS SQS and Lambda

While playing around with Terraform, I realised how hard it is to find a simple working example for spinning up a Lambda function triggered by SQS messages.
As a way to consolidate my learnings, I decided to write this small [blog post](https://dguerri.github.io/random-tech-stuff/Terraform%20-%20AWS%20Lambda%20via%20SQS/).

This repository contains reference code for that post.

## Usage

Create an AWS profile named `terraform_test`, deploy the infra with:

```
terraform init
terraform apply
```

Destroy with

```
terraform destroy
```
