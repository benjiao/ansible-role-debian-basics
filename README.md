# Ansible Role: Debian Basics

Disclaimer: This role is still UNDER DEVELOPMENT.

An Ansible role that sets up my common Debian packages. Will install the following packages: locales, wget, vim, htop.

## Requirements
None

## Variables
```
debian_basics_locale: en_US.UTF-8
```

## Example Playbook

```
- hosts: all
  roles:
    - benjiao.debian-basics
```
