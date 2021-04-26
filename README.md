# sbog/prometheus_server

[![Build Status](https://travis-ci.com/sorrowless/ansible_prometheus_server.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_prometheus_server)
[![Ansible Role](https://img.shields.io/ansible/role/54493)](https://galaxy.ansible.com/sorrowless/prometheus_server)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/54493)](https://galaxy.ansible.com/sorrowless/prometheus_server)
[![Ansible Role](https://img.shields.io/ansible/role/d/54493)](https://galaxy.ansible.com/sorrowless/prometheus_server)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_prometheus_server)](https://github.com/sorrowless/ansible_prometheus_server/blob/master/LICENSE)

An Ansible role which installs and configures [prometheus_server](https://prometheus.io/) on Linux

## Requirements

Ansible 2.8+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure prometheus_server DB
  hosts: prometheus_servers
  remote_user: root

  roles:
    - prometheus_server
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
