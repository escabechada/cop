## Prerequisites
Get credentials of openstack
>> source /<path>/cop-ansible-openrc.sh

## Create instance
ansible-playbook playbook.yml

## Destroy instance
ansible-playbook playbook.yml -e "destroy=yes"

## Install virtualenv
- Install packages to compile the Python module: `apt install libsasl2-dev python-dev libldap2-dev libssl-dev`
- Install pip: `apt install python-pip python3-pip`
- Install virtualenv: `apt install virtualenv`
- Install virtualenvwrapper: `apt install virtualenvwrapper`
- Add this line to your .bashrc: `export WORKON_HOME=$HOME/.virtualenvs`

## Create virtualenv
- Create virtualenv: `mkvirtualenv -p /usr/bin/python3 <virtualenv_name>`
- Install requirements packages: `pip install -r requirements.txt`
