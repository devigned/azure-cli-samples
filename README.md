# Azure CLI 2.0 Samples

This is a repo of scripts for illustrating usage of Azure CLI 2.0 and more generally, Azure in Linux.
The intent is to provide real world scripts and scenarios to help folks be successful working with
Azure infrastructure.

If you have an suggestions for scripts or would like to see an example script written, feel free to 
create an issue explaining the goals of the script. I'll try to get to your request as soon as possible.

## Samples
- Scale Sets
  - [PHP app tier provisioned with Ansible](./scaleset-php-ansible/README.md): build a scale set and deploy out some PHP bits
- Virtual Machines
  - [Create VM from custom VHD](./vm-custom-vhd/README.md): upload VHD and create VM from VHD
  - [Restart by tag and async VM creation](./vm-restart-by-tag/README.md): build multiple VMs across groups async and restart them by tag
  
  
## Contributing
If you would like to contribute a script, please feel free to open a pull request.
