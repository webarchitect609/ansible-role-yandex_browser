Ansible Role: Yandex Browser
============================

[![Build Status](https://github.com/webarchitect609/ansible-role-yandex_browser/workflows/build/badge.svg?branch=master)](https://github.com/webarchitect609/ansible-role-yandex_browser/actions?query=workflow%3Abuild)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-yandex_browser?sort=semver)](https://github.com/webarchitect609/ansible-role-yandex_browser/releases)
[![Downloads](https://img.shields.io/ansible/role/d/56021)](https://galaxy.ansible.com/webarchitect609/yandex_browser)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-yandex_browser)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/webarchitect609)

Installs [Yandex Browser](https://browser.yandex.ru/) from official deb repo.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.yandex_browser }

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
