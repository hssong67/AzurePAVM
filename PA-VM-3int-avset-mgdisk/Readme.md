# Azure-Firewall-into-existing-environment

[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhssong67%2FAzurePAVM%2Fmaster%2FPA-VM-3int-avset-mgdisk%2FAzureDeploy.json)

This template was build to deploy of a 3 interfaces Palo Alto Networks firewall into an existing Microsoft Azure environment that has the following items already deployed:

                    -VNET - with subnets (mamagement, untrust and trust)
                    -Storage Account for the firewall - managed disk
                    -Resource Group for Firewall
                    -Availablitiy Set
                    
It is required to match the name of above items and subnet prefix.

This template is not providing a PIP. If you don't have VGW or Express Route, you will need to create PIP and attath it to the management interface of VM to access it.