# Azure-Terraform-StackSimplify
 Learning to use Terraform with Azure

 # Initial Azure Login Process
 Run the following commands:
 ```t
 az cloud set --name AzureUSGovernment
 az login
 ```


 # Set active Subscription
 List subscriptions with the following command:
 ```t
 az account list --output table
 ```
 
 Copy the ID or Name of the subscription you want to use and run the following command:
 ```t
 az account set --subscription "<copied information>"
 ```