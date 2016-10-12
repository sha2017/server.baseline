Role Name
=========

Baseline, does install basic system utilities on the destination

Requirements
------------

Just make sure Ansible has access.

Example Playbook
----------------

    - hosts: all
      roles:
        - server.baseline

TODO
----

- Also include network configuration for base VMs

License
-------

WTFPL

Author
------
Peter Tambach, piele@sha2017.org
