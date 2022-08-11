After Installing Ansible 

Check Ansible version
 "ansible --version"

Add hosts
Hosts file will be at /etc/ansible
Edit hosts file "vi /etc/ansible/hosts" and add hosts I.P addresses 

Now ping ansible hosts
"ansible hosts -m ping all"
