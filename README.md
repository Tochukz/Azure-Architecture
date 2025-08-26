# Azure Architecture

[Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview?tabs=bicep)  

## Getting Started
__Installing Azure CLI__
Download the MSI Installer from [Microsoft Installer](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest&pivots=msi)  
Verify that installation was successfull
```bash
$ az --version
```

__Installing Bicep Extension__
Install the [Bicep VS Code Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep)  in your VS Code Editor.  

__Azure CLI and Bicep__  
Install Bicep using Azure CLI
```bash
$ az bicep install
```

To validate your Bicep CLI installation, use:
```bash
$ az bicep version
```

To upgrade to the lastest version
```bash
$ az bicep upgrade
```

__Standalone Bicep__  
You can install a standalone Bicep CLI using a downloaded MSI installer, [Bicep Window Installer](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install#windows) or your can use _chocolatey_  
```bash
$ choco install bicep
```

Now you can run _bicep__ commands without running it under Azure CLI
```bash
$ bicep --version
```
