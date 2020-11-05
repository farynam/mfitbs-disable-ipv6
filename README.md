Role Name
=========

Disables ipv6 on a selected machine. 

Requirements
------------

 Ansible: 2.4

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

    - name: Install docker
      hosts: node1, node2, node3
      roles:
      - role: farynam.mfitbs_disable_ipv6

License
-------

MIT

Author Information
------------------

Marcin Faryna
