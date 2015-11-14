fail2ban
========

Installs, configures, and enables fail2ban.

Dependencies
------------

Role dependencies:

 * repo_epel

Role Variables
--------------

n/a

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: fail2ban }

