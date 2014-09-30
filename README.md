AlexanderAllen/JavaScriptDevelopment
=============

Ansible role JavaScript development using Node.js and various front-end libraries.

Requirements
------------

- Ubuntu

Role Variables
--------------

This role inherits from `AlexanderAllen.Liara` various PHP configuration variables.

Dependencies
------------

This role depends on `AlexanderAllen.Liara` role for various PHP configuration variables.

Example Playbook
----------------

    - hosts: webservers
      roles:
         - { role: AlexanderAllen.Liara }
         - { role: AlexanderAllen.Liara-Benchmarking }

License
-------

GPLv2

Author Information
------------------

https://github.com/AlexanderAllen
