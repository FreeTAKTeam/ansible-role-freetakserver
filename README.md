![CI](https://github.com/FreeTAKTeam/ansible-role-freetakserver/actions/workflows/ci.yml/badge.svg)

# ansible-role-freetakserver

FreeTAKServer is a collection of 3 services:

1. Free TAK Server (FTS)
1. Free TAK Server User Interface (FTS UI)
1. Web Map for FTS UI

## Ansible Galaxy Installation

```
ansible-galaxy install jonaugustine.freetakserver
```

## Example Playbook

```
- hosts: freetakserver
  roles:
     - { jonaugustine.freetakserver }
```
