Apache2_Ansible

Repository containing example roles to setup Apache2 on hosts sets in inventories.

Branches:
main - Setup servers using roles
playbook - Setup servers using playbooks

Branch Main
To use this repository set "ansible_host" in inventories directory.
Use this command to setup apache2 on webservers and loadbalancers hosts:
    ansible-playbook setup-app-roles.yml

Use this command to setup loadbalancer on loadbalancers hosts:
    ansible-playbook setup-lb-roles.yml

Branch playbooks:
To use this repository set "ansible_host" in inventories directory.
Use this command to setup apache2 and ladbalancer on webservers and loadbalancers hosts:
    ansible-playbook /playbooks/all-playbooks.yml
