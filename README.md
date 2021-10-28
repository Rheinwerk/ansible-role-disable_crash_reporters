Disable Crash Reporters
=========

This role can be used to disable the Ubuntu crash reporter daemons Whoopsie and Apport.

[![Build Status](https://github.com/Rheinwerk/ansible-role-disable_crash_reporters/actions/workflows/ci.yml/badge.svg)](https://github.com/Rheinwerk/ansible-role-disable_crash_reporters/actions/workflows/ci.yml)

Requirements
------------

None.


Role Variables
--------------

There is one main variable that drives this role: `_disable_crash_reporters`. It is a map that contains all configuration and settings for this role.  Please see `defaults/main.yml` for details.


Dependencies
------------

None.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
        DISABLE_CRASH_REPORTERS: ...
      roles:
         - { role: disable_crash_reporters, tags: [ 'disable_crash_reporters' ], _disable_crash_reporters: "{{ DISABLE_CRASH_REPORTERS }}" }

License
-------

Please see LICENSE.

Author Information
------------------

Original author is [Daniel Schneller](https://github.com/dschneller) as member of the [Rheinwerk](https://github.com/Rheinwerk) project.

