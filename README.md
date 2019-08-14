---
page_type: sample
languages:
- java
products:
- azure
services: Compute
platforms: dotnet
author: yaohaizh
---

# Getting started on managing Azure VM from a virtual machine using with managed service identity (MSI) credentials #

          Azure Compute sample for managing virtual machine from Managed Service Identity (MSI) enabled virtual machine -
            - Create a virtual machine using MSI credentials from System assigned or User Assigned MSI enabled VM.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-dotnet-manage-vm-from-vm-with-msi-credentials.git

    cd compute-dotnet-manage-vm-from-vm-with-msi-credentials

    dotnet build

    bin\Debug\net452\ManageVirtualMachineFromMSIEnabledVirtualMachine.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.