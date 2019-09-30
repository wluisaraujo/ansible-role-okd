[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-OKD-blue.svg)](https://galaxy.ansible.com/wluisaraujo/okd) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-okd.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-okd)

# Infrastructure as Code: with [Ansible](https://www.ansible.com) role to for OpenShift Cluster Environment [OKD](https://www.okd.io/)
------------

Description
------------

 *

Requerimento
------------

 * Sistemas operacionais RedHat, CentOS, Fedora Release 7 ou Superior
 * Docker
 * Resolução dns para os nomes dos hosts.

Installation
------------

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.okd
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.okd/requirements.txt
```

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
    - okd
...
```

Examplo Cenário
----------------


1 host master

2 hosts app-node



----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
