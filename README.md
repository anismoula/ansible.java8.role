Java 8 Ansible Role
=========
Install Java 8 for Debian/Ubuntu Linux Servers

Requirements
------------

None 


Role Variables
--------------


Dependencies
------------

None

Example Playbook
----------------


---
- hosts: host
  gather_facts: no
  become: yes
  roles:
    - ansible.java8.role


License
-------

MIT

Author Information
------------------

This role was created in 2018 by Moula Anis, System and Network Administrator.
