![Ansible Lint](https://github.com/johanneskastl/ansible-role-prepare_first_caasp_master/workflows/Ansible%20Lint/badge.svg)

prepare_first_caasp_master
=========

Install the SUSE-CaaSP-Management pattern required on the first master of a CaaSP cluster, to start the bootstrapping.

Requirements
------------

SUSE CaaSP is only available as an extension for SUSE Linux Enterprise Server 15 SP1.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: 'johanneskastl.prepare_first_caasp_master'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
