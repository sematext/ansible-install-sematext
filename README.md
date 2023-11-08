Ansible Sematext Agent Install Role
=========================================

Install Sematext Agent.

Dependencies
------------
None

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

Need help?
------------------

support@sematext.com
