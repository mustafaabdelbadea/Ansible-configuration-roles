

<div align="center">
<div>
<h1>
Web Application Configuration using Ansible
</h1>
</div>

  <a href="https://github.com/mustafaabdelbadea/Ansible-configuration-roles">
    <img src="./motd/files/ansible.png" alt="Logo" width="400" height="200">
  </a>
  
  </div>

A server configuration by installing nginx and create templates, copy files to machine
Init the project using Ansible Galaxy 
```
ansible-galaxy init
```

Requirements
------------

 - To Run ansible configuration
 - Os any linux distribution
 - Install ansible 
 - Change in inventory file the ip of the mahcine 
 - Change in ansible.config the username and password for the machine  
Role Variables
--------------
- Variables located in motd/default/main.yml

Run
--------------
```
ansible-playbook web-role.yml
```


Example Playbook
----------------

    - hosts: servers
      roles:
         - motd

License
-------

BSD

