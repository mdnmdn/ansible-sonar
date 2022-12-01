# Introduction 

Setup sonarqube server 

# Prerequisites

- Install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)


# Setup the software via ansible

```sh
ansible-playbook -i hosts.ini playbook.yml -u root
```


# Disclaimer

There are several point of improvements:

- remove hosts.ini
- check the users in the ansibile configurations for all services
