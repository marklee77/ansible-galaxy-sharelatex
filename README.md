marklee77.sharelatex
====================

The purpose of this role is to install sharelatex to a web server and enable
access with nginx. The sharelatex server name can be specified by changing the
sharelatex_hostname variable in vars/main.yml.

Role Variables
--------------

- sharelatex_hostname: hostname that sharelatex will service, will be set to 
                       "sharelatex" by default
- sharelatex_port: hostname that sharelatex will service, will be set to 8888 by 
               default.

Example Playbook
----------------

    - hosts: all
      sudo: True
      roles:
        - sharelatex

Try it Out
----------

Check out the github repository, vagrant up, and load http://localhost:8888 in
your web browser.

License
-------

GPLv2

Author Information
------------------

http://stillwell.me

