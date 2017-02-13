ansible-ffwd
=========

An ansible role to install ffwd with all the pre-requisites.

Role Variables
--------------

The default set of variables are available in the defaults/main.yml. Please go through the same if you want to update the default vars. All the vars defined in default section can be overwritten as per the need.

Dependencies
------------

The depenecies are defined clearly in the meta/main.yml. Please go through the same for better understanding.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-ffwd }

Verifying the setup
----------------

To test if your metrics are being registered to ffwd, you can enable debug mode by adding following line in your config:

:debug: {}


Restart ffwd for the changes to take effect. Now you can look at all the data pushed to ffwd by running the following command:

nc localhost 19001


Integration example with C++
----------------

A sampleUdp.c file is available which shows a basic way of sending data to ffwd. You need to compile the code with g++ and simple run the executable. Currently the data that is sent is hard coded in sampleUdp.c

License
-------

BSD
