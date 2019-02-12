awscli
====

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-awscli.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-awscli)

Use this role to install awscli.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    aws_user: __SYSTEM_USER__ (Linux User who should use aws cli)
    aws_region: eu-central-1
    aws_access_key: __ACCESS_KEY__
    aws_secret_key: __SECRET_KEY__


Example Playbook
----------------

    - hosts: awscli
      roles:
         - { role: andrelohmann.awscli }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
