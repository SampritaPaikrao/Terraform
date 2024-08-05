# AWS EC2 Instance Creation Using Terraform

This project provides a simple example of how to create an AWS EC2 instance using Terraform. The configuration includes the main resource definitions in `main.tf`, variable definitions in `variables.tf`, and variable values in `terraform.tfvars`.

1. Install terraform on local system
   https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

2. AWS configuration
    get the AWS_access_key , AWS_secret_key and AWS_ami_Id

3. Create a directory and add 3 files in it i.e. main.tf, variable.tf and variable.tfvars

4. To start the implementation start with :
   
   terraform init --var-file="variable.tfvars"

   
   terraform plan --var-file="variable.tfvars"

   
   terraform apply --var-file="variable.tfvars"

   

6. to check whether the instance is created or not, go to the AWS console and check for the instance.

7. To delete the created instance use :
    terraform destroy --var-file="variable.tfvars"
