# Exercise 1
In this exercise, we are going to install the terraform client on our desktop.

## for macs, I'm using brew 
```bash
$ brew install terraform
$ terraform --version
```

## for linux
Different version of linux, you might need to download different package, which can be found here: https://www.terraform.io/downloads.html. This example is on an ubuntu 16.04 server.
```bash
$ wget https://releases.hashicorp.com/terraform/0.13.5/terraform_0.13.5_linux_amd64.zip
$ unzip terraform_0.13.5_linux_amd64.zip
$ sudo mv terraform /usr/bin/
$ terraform version 
```

## for Windows (well you are on your own, good luck)