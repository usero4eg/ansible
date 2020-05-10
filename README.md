# ansible
Ansible education repo.
All connections using ssh-connection via ssh-key authentication

pub/ # Directory with web-content
group_vars/ # Directory which describe remote-servers
ansible.cfg # Ansible configuration file
hosts       # Remote hosts addreses


playbook1.yml:
Checking server connection via ping from hosts and group_vars

playbook2.yml:
Install Apache web-server on CentOS and enable it on boot

playbook3.yml:
Installing Apache web-server via ansible_os_family dependences ( ansible_os_family == "RedHat" / "Debian" )
Update OS repo (Centos - Epel-Release, Ubuntu - apt-update)
Copying web-server content into /var/www/html directory
Enable service on boot
If web-server content was changed, web-server is restarting

playbook4.yml
Working with strings via vars & debug: section

playbook5.yml
Working with loop & until constructions

playbook6.yml
Same the playbook3.yml, but via block: sections





