## Prerequisites
Get credentials of openstack
>> source /<path>/cop-ansible-openrc.sh

## Create instance
ansible-playbook playbook.yml

## Destroy instance
ansible-playbook playbook.yml -e "destroy=yes"

