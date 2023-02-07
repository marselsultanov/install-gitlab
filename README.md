# Ansible Playbook for install GitLab on Oracle Linux 9

At host (1, 2 and 3 steps is optional):
1. *sudo yum install -y ansible-core*
2. *ansible-galaxy collection install ansible.posix && ansible-galaxy collection install community.general*
3. git clone https://github.com/marselsultanov/gitlab.git && cd gitlab
4. *ansible-playbook reclaim-oled-volume.yml -i localhost, -c=local*
6. dfsdfsdf
