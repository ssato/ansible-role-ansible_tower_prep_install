# ssato.ansible_tower_prep_install

An example ansible role to do preparation for Ansible Tower installation.

<!--
How to get the role ID:
ansible-galaxy info ssato.generate_kickstart | sed -nr "s/[[:blank:]]+id: ([[:digit:]]+)/\1/p"
-->
<!--
[![Build Status](https://img.shields.io/travis/ssato/ansible_role_ansible_tower_prep_install.png)](https://travis-ci.org/ssato/ansible-role-ansible_tower_prep_install) [![Ansible Galaxy](https://img.shields.io/ansible/role/43970.svg)](https://galaxy.ansible.com/ssato/nw_backup_config)
-->

## Requirements

- RHEL 7 or 8 Server
- reposync in yum-utils (RHEL 7) or dnf-plugins-core (RHEL 8)

## Role Variables

see defaults/main.yml for default definitions of each variables and some examples.

## Example

see tests/main.yml for a playbook example.

## License

MIT

## Author

Satoru SATOH (<https://github.com/ssato>)

<!-- vim:sw=2:ts=2:et:
-->
