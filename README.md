# ansible-php7.3-python-docker
Ansible playbook to install php7.3, python 2, and docker

### Description
Simple ansible playbook to install php7.3, python 2, and docker on centos 7 machine

### Execute
ansible-playbook -i <path/to/host-inventory.ini> playbook.yml

### Extra
If you need to install other php extensions, please check out the php7.3-extensions.txt where you can add specific php extension(s) to be installed.
