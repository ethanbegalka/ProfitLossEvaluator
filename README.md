﻿# ProfitLossEvaluator

How to implement:
* Install and Configure Terraform (https://learn.hashicorp.com/collections/terraform/aws-get-started)
* Using an admin role, or a role with necessary permissions, and substitute EthanAdminUser in the code with your role/user. (This is required for managing the KMS key via terraform)
* `terraform init`
* `terraform plan`
* `terraform apply`
* Create a secret called "finnhub_api_key", include your API key from https://finnhub.io/, then configure the secret to be secured by the KMS key "tf_ple_kms_key" 
