# Scripts

# docker-script.sh
Command : bash docker-script.sh

Use: To install Docker Latest version on Debian

# ansible

Steps:
1. Go to environments/common/group_vars/common file and change user and home path accordingly
2. Run **sudo ansible-playbook kubernetes-master.yml -i environments/common** command to install kubernetes on master node
3. Run **kubectl get nodes** to check if master node is ready
