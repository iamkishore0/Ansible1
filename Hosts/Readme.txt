After Installing Ansible 

Check Ansible version
 "ansible --version"

Add hosts
Hosts file will be at /etc/ansible
Edit hosts file "vi /etc/ansible/hosts" and add hosts I.P addresses 

Mentioning hosts in host file
[name of the host]
<pvt ip>  ansible_user=<username>

Now ping ansible hosts
"ansible -m ping all"

