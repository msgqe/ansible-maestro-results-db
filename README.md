Role Name
=========

This role installs the Maestro results DB client in Java.

**Note**: It only installs the client. The DB installation is not provided as part of this
role.

Build/Test Status
------------

Linux Build Status: [![Linux Build Status](https://api.travis-ci.org/msgqe/ansible-maestro-results-db.svg?branch=master)](https://travis-ci.org/msgqe/ansible-maestro-results-db)

Requirements
------------

The package libselinux-python is required for running the test.

Role Variables
--------------

None.


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  - hosts: localhost
    remote_user: root
    roles:
      - ansible-maestro-results-db

License
-------

Apache 2.0

Author Information
------------------

Messaging team @ redhat.com
