# zmr-provision_vm

This role is just and exercise. It deploy a VM with its own key and SG if not alredy present.

# Requirements

* AWS credential
* Ansible >= 2.5
* boto
* boto3
* python >= 2.6

# Role Variables

See default/main.yml for example

    keypair_name: "my_aws_keypair"
    instance_type: t2.micro
    aws_ec2_id: "my_instance_id"
    security_group: "my_aws_sg"
    ami_image: ami-0bdb1d6c15a40392c
    aws_region: eu-west-1

The default image is AMI Linux 2, and default region is AWS Ireland.

AWS credentials are stored in a vars file to be easily encrypted as needed

    aws_access_key: "my_aws_access_key"
    aws_secret_key: "my_aws_secret_key"

