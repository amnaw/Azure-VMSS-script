# Azure VMSS Script

This Azure CLI script create a VMSS with 2 VMs and other related resources. 
It uses cloud-init.txt file while running the command "az vmss create" available in the setup-script.sh  
The cloud-init.txt will install and start the nginx server (a load balancer) and a few Python packages.  
```
az login
chmod +x setup-script.sh
./setup-script.sh
```
reference : [nd081-c4-azure-performance-project-starter](https://github.com/udacity/nd081-c4-azure-performance-project-starter/blob/master/cloud-init.txt)
