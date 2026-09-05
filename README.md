# Ansible Role: proxmox

[![Lint](https://github.com/dcjulian29/ansible-role-proxmox/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-proxmox/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-proxmox.svg)](https://github.com/dcjulian29/ansible-role-proxmox/issues)

Ansible role to provision a Proxmox cluster

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.proxmox
  src: https://github.com/dcjulian29/ansible-role-proxmox.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
