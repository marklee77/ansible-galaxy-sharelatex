Role Name
========

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
-------------------------

Including an example of how to use your role (for instance, with variables 
passed in as parameters) is always nice for users too:

    - hosts: default
      sudo: True
      roles:
        - sharelatex

Try it Out
---------------------------

Check out the github repository, vagrant up, and load http://localhost:8888 in
your web browser.

License
-------

Affero GPL

Author Information
------------------

http://marklee77.github.io

