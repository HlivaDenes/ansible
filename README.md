#/bin/bash
# Az Ubuntu 18.04 munkaállomás kezelése az Ansible programmal.

#### Ansible telepítése:

sudo apt-get -y install software-properties-common

sudo apt-add-repository ppa:ansible/ansible -y

sudo apt-get update -y

sudo apt-get install -y ansible

#### script indítás:

sudo ansible-pull -U https://github.com/englert/ansible.git

