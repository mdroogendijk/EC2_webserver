EC2 webserver instances
=======================

An experiment of provisioning, installing and configuration of AWS EC2 webserver instances.

Requirements
------------

- AWS private key
- ansible-vault configured with AWS keys

Dependencies
------------

AWS (Free Tier) account.

Example
------------

ansible-playbook awsweb.yml

...

PLAY RECAP *********************************************************************
<ip address>               : ok=2    changed=0    unreachable=0    failed=0   
<ip address>               : ok=2    changed=0    unreachable=0    failed=0   
localhost                  : ok=7    changed=1    unreachable=0    failed=0   
