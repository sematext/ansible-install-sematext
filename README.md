Ansible Sematext SPM Monitor Install Role
=========================================

Install Sematext SPM Monitor.

Dependencies
------------
None

Example Playbooks
-------------------------
```
- hosts: all
  become: yes
  roles:
    - { role: sematext.spm-monitor-install}
```

License
-------

Apache2

Author Information
------------------

Ciprian Hacman <ciprian.hacman@sematext.com>
