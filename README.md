## Prerequisite ##
1. Install terraform - https://www.terraform.io/downloads
2. Install Python if not already done https://www.python.org/downloads/
3. Install aws cli - https://docs.aws.amazon.com/cli/v1/userguide/install-macos.html
4. Create access key for terraform https://aws.amazon.com/console/
5. Run - terraform init
6. terraform plan -out "file.plan"
7. terraform apply
8. terraform destroy

Folder Stucture Explaination
1. Main.tf - The main.tf file is the starting point where you will implement the logic of infrastructure as code. This file will include Terraform resources, but it can also contain datasources and locals.
2. Variables.tf - The variables.tf file includes the definitions of input variables for your configuration, mentioning their types, descriptions, and default values.
3. Outputs.tf - The outputs.tf file is used to define output values that expose information about the resources created by a Terraform configuration.