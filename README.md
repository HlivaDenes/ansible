## sudo ansible-pull -U https://github.com/englert/ansible.git

# Ubuntu 18.04 munkaállomás-konfiguráció kezelése az Ansible programmal

Ansible telepítése:

```bash
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

majd:

```bash
sudo ansible-pull -U https://github.com/englert/ansible.git
```
