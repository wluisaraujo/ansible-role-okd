[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-OKD-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-gitlab) [![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-okd.svg?branch=master)]

# Infrastructure as Code: with [Ansible](https://www.ansible.com) role to for OpenShift Cluster Environment [OKD](https://www.okd.io/)
------------

Description
------------

 *

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* docker

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars_files:
    - vars/main.yml 
  roles:
    - iac-ansible-okd
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
