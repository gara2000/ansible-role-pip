PIP
=========

Install `pip` on ubuntu

Requirements
------------

- Should run on Ubuntu distribution

Role Variables
--------------

This role can 1 variables to be set:
- pip_package [default: python3-pip]

Dependencies
------------

No dependencies

Example Playbook
----------------
```bash
- hosts: servers
  become: yes
  vars:
    pip_package: python3-pip
  roles:
      - gara2000.pip
```

License
-------

BSD