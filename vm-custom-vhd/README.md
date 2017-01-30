# Create a Virtual Machine with a custom .VHD

This example creates a virtual machine based off a custom VHD. The prepared VHD is uploaded to a 
newly created storage account and container and the VM user's (deploy user) ssh public key is 
replaced with the executor of the scripts public key.

## To run this sample
`./vm-custom-vhd`

## To tear down this sample
`az group delete -n az-cli-custom-vhd`