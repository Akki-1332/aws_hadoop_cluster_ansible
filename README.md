# aws_hadoop_cluster_ansible
=> Benefits of using this repository..
1. You can clone it anywhere , it will run without any error.
2. You don't require to know anything about Ansible or Hadoop.

This repository will help you to setup you Map-Reduce and HDFS cluster on AWS with the help of ANSIBLE Playbooks.
## You need to change some of the files 📂 
1. `/hadoop_setup/playbook/nodes.txt` 
2. `/aws`
3. make `./aws_hosts/ec2.py` file executable with the command `chmod +x ec2.py`
4. upload your ssh key in `aws_host` folder.
5. change the permission of key `chmod 400 <key_name>`
6. change the name of `ssh-key` in `playbook/ansible.cfg`.
