# Terraform script for creating VPC, Subnets, Internet gateway, Nat gateway, EKS cluster and Wordpress application. 

I have differentiated the code as 2 main repos one is purely for infrastruture creation and other one is for application deployment using Helm 

**Infrastruture Code has 4 folders in it** 

Main.tf -- Contains all the code required for creating VPC, Subnets, Internet gateway, nat gateway and kubernetes cluster.
output.tf -- Contains all the output components 
variables.tf -- Contains all the required variables for the execution of the script 
versions.tf -- Specified all the provider versions required for the terraform execution. 

**Helm code for deployment** 

