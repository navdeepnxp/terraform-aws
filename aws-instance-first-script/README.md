# aws-instance-first-script

![](https://github.com/navdeepnxp/terraform-aws.git/badge.svg)

A Terraform module for creating AWS EC2 instance.

## Usage

```hcl
module "ec2_instance" {
  source     = "git::https://github.com/navdeepnxp/terraform-aws.git/aws-instance-first-script"

  region    = "us-west-2"
}
```

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| region | AWS region | string | ap-southeast-2 | yes |
