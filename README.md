# jtprogru.yc_cli

[![Release to Ansible Galaxy](https://github.com/jtprogru/yc_cli/actions/workflows/galaxy.yml/badge.svg)](https://github.com/jtprogru/yc_cli/actions/workflows/galaxy.yml)
[![TODO 2 Issue](https://github.com/jtprogru/yc_cli/actions/workflows/todo.yml/badge.svg)](https://github.com/jtprogru/yc_cli/actions/workflows/todo.yml)
![GitHub](https://img.shields.io/github/license/jtprogru/yc_cli)
[![Ansible Role](https://img.shields.io/ansible/role/54362)](https://galaxy.ansible.com/jtprogru/yc_cli/)
[![GitHub tag](https://img.shields.io/github/tag/jtprogru/yc_cli.svg)](https://github.com/jtprogru/yc_cli/tags)

This is simple ansible role for installation Yandex Cloud CLI.


## Role Variables


See [`defaults/main.yml`](defaults/main.yml).


## Example Playbook

Example playbook:
```yaml
---
- name: Sample play
  hosts: all
  become: true

  vars:
    foo: bar

  roles:
    - jtprogru.yc_cli
```

## Authors

- Michael Savin
  - :octocat: [@jtprogru](https://www.github.com/jtprogru)
  - :bird: [@jtprogru](https://www.twitter.com/jtprogru)
  - :moneybag: [savinmi.ru](https://savinmi.ru)

## License

See [LICENSE](LICENSE.md)
