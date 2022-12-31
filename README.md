# ansible_tutorial

## Useful Commands


```
ansible all -m gather_facts --limit 192.168.254.156 | grep ansible_distribution
```

```
systemctl status mariadb
```

```
ansible-playbook --list-tags install_apache.yml
```

<p>&nbsp;</p>

## Reference 

- [Deploy a web server apache httpd on RedHat-like systems - Ansible modules yum, copy, service firewalld](https://www.ansiblepilot.com/articles/deploy-a-web-server-apache-httpd-on-redhat-like-systems-ansible-modules-yum-copy-service-firewalld/i) 
- [Install PHP 8.0 on Centos 7 using Ansible – How to do](https://bobcares.com/blog/install-php-8-0-on-centos-7-using-ansible/)
- [ansible_distribution is wrongly reported as 'RedHat' under CentOS 7.1 #10937](https://github.com/ansible/ansible/issues/10937)
- [Installing MariaDB Using Ansible](https://www.theurbanpenguin.com/installing-mariadb-using-ansible/)  
 


