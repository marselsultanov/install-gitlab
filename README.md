# Ansible Playbook for install GitLab on Oracle Linux 9

ansible-playbook playbook.yml -i hostname, --private-key id_rsa --ssh-extra-args "-o stricthostkeychecking=false"
