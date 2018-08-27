Hashcat
=========

Installs Hashcat and nVidia drivers.

Requirements
------------

No hard requirements, but this was built and tested against an AWS EC2 p3.8xlarge instance running Ubuntu 16.04 LTS. Currently supports nVidia GPUs only.

Role Variables
--------------

  hashcat_git_location: '/opt'

Dependencies
------------

- `leesoh.git`

Example Playbook
----------------

```yml
  - hosts: servers
    roles:
    - leesoh.hashcat
```

License
-------

MIT

Author Information
------------------

Hashcat: https://hashcat.net
