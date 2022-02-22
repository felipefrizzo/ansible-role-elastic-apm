Ansible Elastic APM Server
=========

Ansible role for download and configure Elastic APM Server.

Requirements
------------

* Ansible >= 2.9

Role Variables
--------------

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) and are listed in the table below.
| Name | Default Value | Description |
| ---- | ------------- | ----------- |
| `elastic_apm_version` | 6.4.0 | Elastic APM Server package version |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - felipefrizzo.elastic_apm

License
-------

This project is licensed under MIT License. See LICENSE for more details.
