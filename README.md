# CST8918 - Lab A11: Remote State Storage with Azure Blob Storage

This lab demonstrates how to configure remote state management for Terraform using Azure Blob Storage. The state file is stored securely in a container and shared across the team using a backend configuration.

## Lab Objectives

- Create a dedicated resource group for Terraform backend
- Provision an Azure storage account and container
- Configure Terraform to use Azure Blob Storage as backend
- Deploy infrastructure using remote state
- Verify and submit the state file before destroying resources

## Screenshot of Remote State File in Azure Blob

This screenshot shows the overview panel for the `dev.terraform.tfstate` file stored in the `tfstate` container:

![Remote state file in Azure Blob](overview%20panel-dev.terraform.PNG)

## Notes

- The state file is stored in Azure Blob Storage and is not included in this repository.
- The `terraform destroy` command was executed after submission, and the blob still remains as per lab requirements.

## Submission Files

- Screenshot of blob overview panel with user profile visible
- Downloaded copy of `dev.terraform.tfstate` file (submitted via Brightspace)


