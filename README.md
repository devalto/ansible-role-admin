# devalto.admin

[![Ansible Role](https://img.shields.io/ansible/role/9598.svg?maxAge=2592000)](https://galaxy.ansible.com/devalto/redis/)

This is a Ansible role to configure admin users

## Requirements

Ansible 2.x

## Role Variables

|Variable|Description|Default|
|---|---|---|
|```admin_groups```||adm,sudo|

## Dependencies

none

## Example Playbook

    - hosts: servers
      var:
        admin_users:
          - name: username
            authorized_keys: public_key
      roles:
         - { role: devalto.admin }

## Author Information

Yanick Châteauvert
