ansible-firewall
================

[![Build Status](https://travis-ci.org/galexrt/ansible-.svg?branch=master)](https://travis-ci.org/galexrt/ansible-)

A try at at an Ansible ipset and iptables managing role.

Requirements
------------

All systems need to use `systemd` as the service controller.

Role Variables
--------------

For all available variables take a look at the `defaults/main.yml`.

Dependencies
------------

This role has a dependency on my `common-facts` role.
You can see it [here](https://github.com/galexrt/ansible-common-facts).

Example Playbook
----------------

An example playbook on how to use this role:

    - hosts: servers
      roles:
         - { role: galexrt.firewall }

License
-------

Apache 2.0 License

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
