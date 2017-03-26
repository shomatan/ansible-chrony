Ansible role: NTP server/client
=========

Installs versatile implementation of the Network Time Protocol (NTP).

Requirements
------------

None.

Role Variables
--------------

    chrony_servers:
      - ntp.nict.jp
    chrony_allow_networks: []

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.chrony }

License
-------

MIT

Author Information
------------------
