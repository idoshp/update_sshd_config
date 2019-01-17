# update_sshd_config
Ansible playbook for modify sshd config with templates


#### Description

- Ansible playbook for modify sshd config with templates



#### prerequisites

- Ansible Installed >v2.4.
- create inventory file with your target server with a group tag:
  [my_hosts]
  server1
- update the main.yml under var folder with the value of the.

#### execute via cli

- change the tage per the role you want: ansible-playbook -i inventory.ini sshd_config.yml --tags "rhel6.6"

