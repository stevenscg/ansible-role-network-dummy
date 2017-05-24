network-dummy
=============

This is used to create a dummy0 network interface that both
consul and dnsmasq can bind to in a scenario where consul
runs on a docker host and the containers on that host need
access to consul.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: network-dummy }

License
-------

MIT
