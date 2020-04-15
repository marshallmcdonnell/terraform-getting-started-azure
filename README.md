# Terraform "Getting Started" for Azure

These are my scripts from going over Terraform's ["Getting Started"](https://learn.hashicorp.com/terraform?track=azure#azure) via Azure Linux VM instances

This currently uses the local, [Azure CLI method for authentication](https://www.terraform.io/docs/providers/azurerm/guides/azure_cli.html)

## Pre-requisites for Azure

First steps are:
  1) Insall the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest)
  2) Login to Azure via the CLI
        ```
        az login
        ```

# Quickstart

  0) [Install Terraform](https://learn.hashicorp.com/terraform/getting-started/install.html)
  1) Clone this repo
  2) Initialize: 
        ```
        terraform init
        ```
  3) Make sure you are logged in to Azure via the CLI (i.e. `az login`)
  4) Review and apply changes to resources: 
        ```
        terraform apply
        ```
  5) Tear down resources: 
        ```
        terraform destroy
        ```


