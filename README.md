gitleaks
========

Install gitleaks via existing repo and if not found directly from github.
If already installed it currently will not upgrade the existing version.

Tested on
- Debian
- Ubuntu
- CentOS
- Almalinux

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

   - hosts: servers-using-git\
     roles:
       - role: arikkert.gitleaks


License
-------

BSD

Author Information
------------------

    ARK-ICT
    Andre Rikkert de Koe - ICT
