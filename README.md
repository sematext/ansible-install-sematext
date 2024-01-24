Ansible Sematext Agent Install Role
=========================================

Install Sematext Agent.

Dependencies
------------
None

Example Playbooks
-------------------------

Before executing your playbook, make sure that `infra_token` var has a value of your infra token found in Agent Setup (Fleet & Discovery) instructions. 

```
- hosts: all
  gather_facts: yes
  become: yes
  vars:
    infra_token: INFRA_TOKEN
  roles:
    - { role: sematext.spm-monitor-install }
```

License
-------

Apache2

Need help?
------------------

support@sematext.com
