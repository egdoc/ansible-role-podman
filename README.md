Ansible Role: podman
=========
[![CI](https://github.com/egdoc/ansible-role-podman/actions/workflows/ci.yml/badge.svg)](https://github.com/egdoc/ansible-role-podman/actions/workflows/ci.yml)

Ansible role to install and setup Podman on Linux

Requirements
------------

None

Role Variables
--------------

see [meta/argument_specs.yml](meta/argument_specs.yml)

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      tasks:
        - name: Import egdoc.podman role
          ansible.builtin.import_role:
            name: egdoc.podman


License
-------

see [meta/main.yml](meta/main.yml)

Author Information
------------------

Created by Egidio Docile