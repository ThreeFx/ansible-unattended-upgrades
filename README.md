unattended-upgrades
=========

Configures automatic security updates on Debian.

Requirements
------------

None.

Role Variables
--------------



| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`unattended_upgrades_reboot` | "false" | Reboot if required by upgrades
`unattended_upgrades_reboot_time` | "03:00" | When to reboot
`unattended_upgrades_blacklist` | [] | Packages to hold back

Dependencies
------------

None.

Example Playbook
----------------

See `molecule/default/playbook.yml`

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
