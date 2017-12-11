SSSD
=========
This role is to configure the System Security Services Daemon in Red Hat Enterprise Linux, CentOS, and Fedora operating systems. 

Requirements
------------
None

Role Variables
--------------
There are a few main configuration variables:

* **sssd**: These are the default sssd configration options, which are placed into /etc/sssd/sssd.conf
* **sssd_domains**: These are the sssd domains, which are placed into /etc/sssd/conf.d/_domain_.conf


Dependencies
------------
To use this role, you must be using Red Hat Enterprise Linux, CentOS, or Fedora. This role currently does not function under Debian derivatives.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: ISU-Ansible.sssd }

License
-------
GPLv2

Author Information
------------------
* Barry Britt <bbritt@iastate.edu>