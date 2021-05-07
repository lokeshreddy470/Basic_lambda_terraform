# Terraform script for creating VPC, Subnets, IGW, Nat gateway, EKS cluster and Wordpress application. 

The code is differentiated in to 2 main repos, one is for infrastruture creation and other one is for application deployment using Helm 

**Infrastruture Code consists 4 files**

Main.tf -- Contains all the code required for creating VPC, Subnets, Internet gateway, nat gateway and kubernetes cluster.

outputs.tf -- Contains the output components 

variables.tf -- Contains the required variables for the execution of the script 

versions.tf -- Specific provider versions required for the terraform execution. 

**Helm code for deployment**

Helm.tf -- Contains configuration related to helm deployment like repository, chart and all other required details. 

provider.tf - Containers aws region and configuration.

plugins.tf -- specified the required version of plugins. 

_**How to excute the script ??**_


_I have created a simple bash script to excute the terraform changes, CD into the folder and excute the infra.sh by running the command_ `sh infra.sh`



