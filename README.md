Ansible Role: Skype
=========

Installs Skype from an official deb repository.

Requirements
------------

None.

Role Variables
--------------

None of variables is needed to be altered for installing latest stable Skype from https://repo.skype.com/deb . 
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

License
-------

MIT

Author Information
------------------

This role was created in 2019 by Gripinskiy Sergey.
