yuriyguts.anaconda
==================

An Ansible role to install Anaconda on Linux, along with additional conda packages of your choice.


Role Variables
--------------

See [defaults/main.yml](defaults/main.yml).

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: modeling
      roles:
        - role: yuriyguts.anaconda
          anaconda_install_packages: 'numpy scikit-learn nltk'

License
-------

MIT

Author Information
------------------

Yuriy Guts ([https://github.com/YuriyGuts](https://github.com/YuriyGuts)).
