# Overview: ansible-role-repo-epel

Installs the [EPEL repository](https://fedoraproject.org/wiki/EPEL) (Extra Packages for Enterprise Linux) for RHEL/CentOS. This role was inspired by the geerlingguy.repo-epel role.

- - - -
# Requirements

This role only is needed/runs on RHEL and its derivatives.

- - - -
# Dependencies

None.

- - - -
# Example Playbook

    - hosts: servers
      roles:
        - pgporada.repo-epel

- - - -
# License and Author Information

GPLv3

Phil Porada - philporada@gmail.com
