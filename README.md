Ansible roles are added abstraction of building your playbook in more modular fashion, where you hide all technicalities by spiliting your tasks into smaller files and grouping them under respective folders of "tasks", "templates", "handlers", "vars", "file", "defaults" etc.

In this begineer project we will create an ansible roles and will use that in our main playbook.

There are two ways to create roles in ansible:
1. first one is from manually creating all file structure under "roles" named folder.
2. second one is from "ansible-galaxy" which  works as a repo of millions of pre-builded roles.


Create your role by: $ ansible-galaxy init sample_role 

**Note: You can always create your inventory file andmention all your remote hosts and you can use them while running playbook with "-i filename" option.

After creating a sample roles you can specify all the required tasks in respective roles. After that you can include them in your master playbook.