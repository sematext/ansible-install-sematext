Ansible Sematext Agent Install Role
=========================================

Install Sematext Agent.

Dependencies
------------
Java must be installed and 'java' must be in the PATH.

Example Playbooks
-------------------------
```
- hosts: all
  gather_facts: yes
  become: yes
  roles:
    - { role: sematext.spm-monitor-install }
```

License
-------

Apache2

Author Information
------------------

Ciprian Hacman <ciprian.hacman@sematext.com>
