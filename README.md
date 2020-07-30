Role Name
=========

Hopla.cloud role for ansible to install a simple elastic search.

Requirements
------------

Ubuntu 18.04

Role Variables
--------------

user_name: "username"
user_email: "exemple@domain.com"

Dependencies
------------

- hoplacloud.linux_update
- hoplacloud.linux_motd
- hoplacloud.fail2ban
- hoplacloud.proftpd
- hoplacloud.postfix
- elastic.elasticsearch

Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.elasticsearch

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
