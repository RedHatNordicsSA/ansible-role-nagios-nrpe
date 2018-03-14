Role Name
=========

This role installs and configures NRPE (Naigos Remote Plugin Execution) daemon.
This allows for easy and more security execution of arbitrary scripts and programs on monitored hosts.

Requirements
------------

The server needs to have access to EPEL, which is default in our environment.

Role Variables
--------------

None, straight forward drop off.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible-role-nagios-nrpe

License
-------

GPL 3.0

Author Information
------------------

Magnus Glantz, sudo@redhat.com, 2018

