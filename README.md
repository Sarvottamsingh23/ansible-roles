# Ansible apache role project

This is a complete example of an Ansible project using a custom role 'apache2' role.

## Usage

1. Edit: 'inventory.ini' with your respective target hosts.
2. Run: 'ansible-playbook playbook.yaml --ask-become-pass'

## Structure

- 'ansible.cfg' - Project Configuration
- 'inventory.ini' - Hosts file
- 'playbook.yaml' - main playbook
- 'roles/apache2' - re-usable role

Created by Sarvottam Kumar! Happy Automation:/

## High level-steps

1. Create a ansible-role skeleton:
$ ansible-galaxy init my_role_name

2. Ensure you have edit all your folder and files. ensure you should have meta/main.yaml and tasks/main.yaml

3. Create Git-Hub repo named like "ansible-role-*" (any repo name with prefix "ansible-role") because ansible-galaxy will look for only this named repo for keeping on your galaxy profile.

4. Push you roles main stucture to github. (Ensure in repo meta folder is there at 1st level itself).

5. Now go to ansible galaxy website. Authenticate with github. Import your created role. And it's done your role is on ansible-galaxy and anyone can use it.
