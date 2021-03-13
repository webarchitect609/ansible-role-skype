Ansible Role: Skype
===================

[![Build Status](https://github.com/webarchitect609/ansible-role-skype/workflows/build/badge.svg?branch=master)](https://github.com/webarchitect609/ansible-role-skype/actions?query=workflow%3Abuild)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-skype?sort=semver)](https://github.com/webarchitect609/ansible-role-skype/releases)
[![Downloads](https://img.shields.io/ansible/role/d/39614)](https://galaxy.ansible.com/webarchitect609/skype)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-skype)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/webarchitect609)

Installs Skype from the official deb repository.

Requirements
------------

None.

Role Variables
--------------

None of the variables need to be altered for installing the latest stable version of the application.
However, all available variables are listed below, along with default values (see `defaults/main.yml`):

    skype_package: skypeforlinux

Package name to install

    skype_deb_source: "deb [arch=amd64] https://repo.skype.com/deb stable main"

Repository url.

    skype_gpg_key_url: "https://repo.skype.com/data/SKYPE-GPG-KEY"

GPG key url.


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.skype }

License & Author Information
-------
[BSD-3-Clause](LICENSE.md)
