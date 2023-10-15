Role Name
=========

install and configure unattended update package

Requirements
------------


Role Variables
--------------
| defaults variable | description |default value|
|-------------------|-------------|-------------|
|apt_conf_dir| apt config dir| /etc/apt/apt.conf.d|
|unattended_config| job config file|50unattended-upgrades|


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-unattended }

License
-------

This project is licensed under the Attribution-NonCommercial-ShareAlike 4.0 International License - see the [LICENSE.md](LICENSE.md) file for details

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
