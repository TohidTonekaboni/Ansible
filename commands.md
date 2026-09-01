#### Initial test

ansible --version

ansible -m ping localhost

ansible-config init --disabled -t all > ansible.config

ansible config view

ansible config list

ansible config dump

#### Ansible-playbook Structure

sudo mkdir -p ansible/provision

sudo chown -R tohid:staff ansible/

ansible-playbook -i inventory/anisahosts myproject.yml