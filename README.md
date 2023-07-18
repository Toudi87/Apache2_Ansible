
# Apache2_Ansible

Repository containing example roles to setup Apache2 on hosts sets in inventories.

## Branches:
<p> <em><strong>main</strong></em> - Setup hosts using roles <br>
<em><strong>playbook</strong></em> - Setup hosts using playbooks </p>

## Branch main:
<p> To use this repository set "ansible_host" in inventories directory. <br>
Use this command to setup apache2 on webservers and loadbalancers hosts: <br>
   <em><strong> ansible-playbook setup-app-roles.yml </strong></em> </p>

<p> Use this command to setup loadbalancer on loadbalancers hosts: <br>
   <em><strong> ansible-playbook setup-lb-roles.yml</strong></em> </p>

## Branch playbooks:
<p>To use this repository set "ansible_host" in inventories directory.<br>
Use this command to setup apache2 and ladbalancer on webservers and loadbalancers hosts:<br>
   <em><strong> ansible-playbook /playbooks/all-playbooks.yml</strong></em></p>
