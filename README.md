Ansible Role: Squid
=========

Ansible role to install Squid Proxy Daemon on Linux Servers.

Requirements
------------

The role does not require anything to run on RHEL and its derivatives.

Role Variables
--------------

Available variables are listed below, along with default values (see ```defaults/main.yml```):

``` yaml
squid_port: 3128
```

```squid_port:``` **(Required)** Port for the Squid Daemon to listen to. **(Default is 3128)**

Role variables can be stored with the hosts.yaml file, or in the main variables file.

Dependencies
------------

None.

Example Playbook
----------------

``` yaml
    - hosts: servers
      roles:
         - role: mikepruett3.squid
```

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-squid)
