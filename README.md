Python
=========

This can be used to install various python versions and configure the default python version.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

- `python_packages`: The python packages to install
- `python_alternatives`: The python alternatives to configure

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - python

License
-------

MIT
