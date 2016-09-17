Homelab VMware/Ubuntu Nested VM Testlab
=======================================

This repository hosts the ansible playbooks that setup a nested ESX server for test use.  I use it for developing my skills.

Requirements
------------

The scripts require a large ESX server with the capacity to support a series of nested servers.

Roles
-----

The site.yml ansible playbook references a series of roles to support the deployment of the ESX and Ubuntu 16.04 templates.  The playbooks include the following:

* Common - Builds a common set of services on Ubuntu
* VMware - Builds the entire VMware stack including networking, data stores, and esx hosts
* TBD

License
-------

BSD

Author Information
------------------

The home lab support my ongoing develop. mailto:cdr67@yahoo.com or @cdrobey
