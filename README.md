# Ansible Playbook for install GitLab on Oracle Linux 9

ansible-playbook playbook.yml -i hostname, --private-key ssh.key --ssh-extra-args "-o StrictHostKeyChecking=false"
