# Exercise 2
For this exercise, we're going to use aws terraform provider

## what are terraform providers?
- Terraform offers a list of providers. 
- A provider is responsible for understanding API interactions and expose resources
- Below we are going to setup the AWS provider. 
- We are going to initialize terraform with the terraform init command. 
- Notice, how the aws provider plugin is downloaded once we do a terraform init

```bash
$ vi provider.tf
provider "aws" {
  version = "~> 3.0"
  region  = "us-east-1"
}
 
$terraform init
```