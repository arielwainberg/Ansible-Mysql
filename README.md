# Ansible-Mysql
<p align="center">
 <img src="https://liquidat.files.wordpress.com/2014/02/ansible_logo_round.png" width="150"/>
 <img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" width="350"/>
</p>


### Deploying mysql with DB, table and record creation using mysql role
.=]Ariel Wainberg[=.



## What it is
* Deployment of MYSQL server using Ansible

## Requirments on destination:
- SSH server
- Python

## Prequesites actions:
1. Be sure ansible host ssh public key is in "authorized_keys" in destination hosts to be able to connect without password.
2. be sure sudoers does not need type password for sudoers actions

## User Guide
1. Clone this repository.
2. customize variables in /mysql/vars/main.yml

