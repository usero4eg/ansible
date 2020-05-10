# ansible
Ansible education repo.
<br><i>All connections using ssh-connection via ssh-key authentication</i>
<ul>
  <li>pub/          # Directory with web-content</li>
  <li>group_vars/   # Directory which describe remote-servers</li>
  <li>ansible.cfg   # Ansible configuration file</li>
  <li>hosts         # Remote hosts addreses</li>
</ul>

<b>playbook1.yml:</b>
Checking server connection via ping from hosts and group_vars

<b>playbook2.yml:</b>
Install Apache web-server on CentOS and enable it on boot

<b>playbook3.yml:</b>
Installing Apache web-server via ansible_os_family dependences ( ansible_os_family == "RedHat" / "Debian" )
Update OS repo (Centos - Epel-Release, Ubuntu - apt-update)
Copying web-server content into /var/www/html directory
Enable service on boot
If web-server content was changed, web-server is restarting

<b>playbook4.yml</b>
Working with strings via vars & debug: section

<b>playbook5.yml</b>
Working with loop & until constructions

<b>playbook6.yml</b>
Same the playbook3.yml, but via block: sections





