# Educación IT - Ansible

Ansible Playbook that creates a Nginx server in a DEV group of servers.

## Comands

- List dev hosts: `ansible -i inventory.ini dev --list-hosts`
- Check ping to dev hosts: `ansible -i inventory.ini dev -m ping -u root`
- Show dev hosts setup: `ansible -i inventory dev -m setup`
- Check playbooks' syntax: `ansible-playbook --syntax-check playbook.yml`
- Apply playbook: `ansible-playbook playbook.yml -i inventory.ini -u root`
