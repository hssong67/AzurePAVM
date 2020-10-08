# Azure-Firewall-into-existing-environment

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/hssong67/AzurePAVM/master/PA-VM-3int-avset-mgdisk-pip%20w%20xl%20NIC/AzureDeploy.json)

This template was build to deploy of a 3 interfaces Palo Alto Networks firewall into an existing Microsoft Azure environment that has the following items already deployed:

                    -VNET - with subnets (mamagement, untrust and trust)
                    -Storage Account for the firewall - managed disk
                    -Resource Group for Firewall
                    -Availablitiy Set
                    
It is required to match the name of above items and subnet prefix.

This template will enable Accelerated Networking on data NICs.
