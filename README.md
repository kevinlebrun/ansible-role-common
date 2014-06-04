Role Name
========

An Ansible role that installs my common configuration on Debian / Ubuntu.

Requirements
------------

None.

Role Variables
--------------

    common_packages

    common_motd_template

    common_deployer_manage
    common_deployer_user
    common_deployer_group
    common_deployer_home
    common_deployer_shell
    common_deployer_public_key

    common_hostname

    common_timezone

Dependencies
------------

None.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: kevinlebrun.common }

License
-------

MIT

Author Information
------------------

This role was created in 2014 by Kevin Le Brun.
