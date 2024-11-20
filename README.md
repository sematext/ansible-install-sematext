Ansible Sematext Agent Install Role
=========================================

Install [Sematext Agent](https://sematext.com/docs/agents/sematext-agent/).

Dependencies
------------
None

Example Playbooks
-------------------------

Before executing your playbook, make sure that the `infra_token` and `region` variables have values according to the [Sematext docs](https://sematext.com/docs/agents/sematext-agent/ansible/#deploying-sematext-agent).

```
- hosts: all
  gather_facts: yes
  become: yes
  vars:
    region: REGION
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
