
# Azure ARM Example

## Description

This repository contains an example of Azure Resource Manager (ARM) template declarations used to build resources in Azure. The provided templates demonstrate how to define and deploy various Azure resources using ARM templates.

## Requirements

- Azure subscription
- Azure CLI or Azure PowerShell

## Mode of Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ferrerallan/azure-arm-example.git
   ```
2. Navigate to the project directory:
   ```bash
   cd azure-arm-example
   ```
3. Customize the `azuredeploy.parameters.json` file with your parameters.
4. Deploy the ARM template using Azure CLI:
   ```bash
   az deployment group create --resource-group <YourResourceGroup> --template-file azuredeploy.json --parameters azuredeploy.parameters.json
   ```

## License

This project is licensed under the MIT License.
