# Ansible Playbook for install GitLab on Oracle Linux 9

For local host:
1. ansible-playbook playbook.yml -i localhost, -c=local

For remote host:
1. ansible-playbook playbook.yml -i hostname, --private-key ssh.key
