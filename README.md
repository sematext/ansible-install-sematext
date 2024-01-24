Ansible Sematext Agent Install Role
=========================================

Install [Sematext Agent](https://sematext.com/docs/agents/sematext-agent/).

Dependencies
------------
None

Example Playbooks
-------------------------

Before executing your playbook, make sure that `infra_token` var has a value of your Infra App's token found in Agent Setup ([Fleet & Discovery](https://sematext.com/docs/fleet/)) instructions. 

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
