# ZMR challenge

This playbook is just and exercise. It create a VM on AWS, then install docker and other required packages and deploy a MariaDB container on it.

Check the roles README for further details.

To run the playbook:

ansible-playbook --vault-id @prompt zmr.yml
