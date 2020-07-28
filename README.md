# Packer Azure Windows Virtual Machine Image

Using Packer to create a Windows Virtual Machine image

## Prerequisites:

* Packer --> https://www.packer.io

* Azure Resource Group

* Azure Service Principal (SPN)

## How to use:

Update the environment variables with your Resource Group and SPN and then execute:

**packer build -var-file=azure-variables.json azure-windows-2016-base.json**
