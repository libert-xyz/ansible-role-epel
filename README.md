## Ansible Role: EPEL
----------------------

[![CI](https://github.com/libert-xyz/ansible-role-epel/workflows/CI/badge.svg?event=push)](https://github.com/libert-xyz/ansible-role-epel/actions?query=workflow%3ACI)

Ansible role to install the EPEL repository in RedHat based distributions.

## Requirements
------------

root access


## Role Variables
--------------

None

## Dependencies
------------

None

## Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
        - libert_xyz.epel


## Compatibility
------------

This role has been tested on these [container images](https://hub.docker.com/u/libertxyz):

|container|tags|
|---------|----|
|centos7|latest|
|centos8|latest|
|amazonlinux2|latest|


## License
 -------

MIT

## Author Information
------------------

This role was created in 2021 by [Libert Schmidt](https://libert.xyz)