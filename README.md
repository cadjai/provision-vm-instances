# provision-vm-instances 
This is a collection of roles and playbooks to help automate the provisioning of VMs to be used for various use cases like deploying a DNS server, a satellite server, a Container Registry, an OCP cluster ....

To install this first use ansible-galaxy to install dependencies like below:
```
ansible-galaxy install -r requirements.yml --roles-path=roles
```
