Hashcat
=========

World's fastest password cracker.

Requirements
------------

No hard requirements, but this was built and tested against an AWS EC2 p3.8xlarge instance running Ubuntu 16.04 LTS.

Role Variables
--------------

hashcat_git_location: '/opt'

Dependencies
------------

leesoh.git

Example Playbook
----------------

 - hosts: servers
   roles:
     - { role: leesoh.hashcat }

License
-------

MIT

Author Information
------------------

Hashcat: https://hashcat.net
