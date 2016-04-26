[![Build Status](https://travis-ci.org/ind9-ops/ffwd.svg?branch=best-check)](https://travis-ci.org/ind9-ops/ffwd)

Role Name
=========

ffwd role depending on ruby-ffwd and monit

Requirements
------------

ruby and certain gems

Role Variables
--------------
ffwd_version
ffwd_base_dir
ffwd_log_dir
ffwd_conf_dir
ffwd_log
ffwd_process_pid_file
ffwd_plugins
ffwd_sinks

Dependencies
------------

ruby_ffwd monit

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
