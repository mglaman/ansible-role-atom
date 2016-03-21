mglaman.atom [![Build Status](https://travis-ci.org/mglaman/ansible-role-atom.svg?branch=master)](https://travis-ci.org/mglaman/ansible-role-atom)
=========

Support for Atom editor and Atom Package Manager via Ansible.

Requirements
------------

None

Role Variables
--------------

````yaml
atom_ver : '1.2.3'
atom_mirror : 'https://github.com/atom/atom/releases/download'
atom_deb_platform : 'amd64'
atom_rpm_platform : 'x86_64'
atom_packages_packages: [ ]
````

Example Playbook
----------------

````yaml
    - hosts: servers
      roles:
         - { role: mglaman.atom }
````

License
-------

MIT

Author Information
------------------

[Matt Glaman](https://glamanate.com)
