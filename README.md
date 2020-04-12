[![Build Status](https://travis-ci.com/c-goes/ansible-role-podman.svg?branch=master)](https://travis-ci.com/c-goes/ansible-role-podman)


podman
=======

Role to install Podman on Ubuntu.

Requirements
------------

Ubuntu LTS


Role Variables
--------------

- `containers_fs` what filesystem to use, choices: `zfs` or `fuse-overlayfs` (default).
- `containers_zfs_fs` what filesystem in ZFS should be used for containers. Default: `zroot/podman`

Dependencies
------------


Example Playbook
----------------

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
