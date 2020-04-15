# Terraform on Azure - Getting Started

This currently uses the local, [Azure CLI method for authentication](https://www.terraform.io/docs/providers/azurerm/guides/azure_cli.html)

## Pre-requisites for Azure

First steps are:
  1) Insall the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest)
  2) Login to Azure via the CLI

    ```
    az login
    ```

  3) Note "id" (== `subscription_id`) and "`tenatId`" (== `tenant_id`)


# Quickstart

  0) [Install Terraform](https://learn.hashicorp.com/terraform/getting-started/install.html)
  1) Run `terraform init` (if first time)
  2) Make sure you are logged in to Azure via the CLI (i.e. `az login`)
  3) Run the plan / apply:

    ```
    terraform plan
    terraform apply
    ```


