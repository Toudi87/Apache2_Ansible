Apache2_Ansible

Repository containing example roles to setup Apache2 on servers sets in inventories.

To use this repository set "ansible_host" in inventories directory.

Use this command to setup apache2 on webservers hosts:
ansible-playbook setup-app-roles.yml

Use this command to setup loadbalancer on loadbalancers hosts:
ansible-playbook setup-lb-roles.yml


Branches:
main - Setup servers using roles
playbook - Setup servers using playbooks