# Terraform script for creating VPC, Subnets, Internet gateway, Nat gateway, EKS cluster and Wordpress application. 

I have differentiated the code as 2 main repos one is purely for infrastruture creation and other one is for application deployment using Helm 

**Infrastruture Code has 4 folders in it** 

Main.tf -- Contains all the code required for creating VPC, Subnets, Internet gateway, nat gateway and kubernetes cluster.
outputs.tf -- Contains all the output components 
variables.tf -- Contains all the required variables for the execution of the script 
versions.tf -- Specified all the provider versions required for the terraform execution. 

**Helm code for deployment** 

Helm.tf -- Contains configuration related to helm deployment like repository, chart and all other required details. 
provider.tf - Containers aws region and configuration 
plugins.tf -- specified the required version of plugins. 

_**How to excute the script ??**_
_
I have created a simple bash script to excute the terraform changes CD into the folder and excute the infra.sh by running the command_ `sh infra.sh`



