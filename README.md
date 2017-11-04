# Development Environment Setup for Phabricator using Vagrant and Ansible

to setup:
1. [Install Virtualbox](https://www.virtualbox.org/wiki/Downloads)
2. [Install Vagrant](https://www.vagrantup.com/intro/getting-started/install.html)
3. [Install Ansible](https://docs.ansible.com/ansible/latest/intro_installation.html)
4. run `vagrant up`
5. get into the machine with `vagrant ssh`

The site will be hosted at http://192.168.100.100:3001

Base image: ubuntu/xenial64 (will be downloaded automatically if not yet downloaded)
Installed tools inside the vm:
 - Apache 2
 - Git
 - Mysql-server
 - PHP 5.6
 - Phabricator
 - Arcanist (Phabricator CLI tool)
 - Libphutil (Collection of PHP library)

