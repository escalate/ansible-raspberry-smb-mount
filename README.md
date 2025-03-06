[![Test](https://github.com/escalate/ansible-raspberry-smb-mount/actions/workflows/test.yml/badge.svg?branch=master&event=push)](https://github.com/escalate/ansible-raspberry-smb-mount/actions/workflows/test.yml)

# Ansible Role: Raspberry - SMB Mount

An Ansible role that manages SMB (Server Message Block) mounts on Raspberry Pi OS (Debian Bookworm).

## Role Variables

Please see [defaults/main.yml](https://github.com/escalate/ansible-raspberry-smb-mount/blob/master/defaults/main.yml) for a complete list of variables that can be overridden.

## Dependencies

This role relies on the following dependencies:

- Roles: None
- Collections: [requirements.yml](https://github.com/escalate/ansible-raspberry-smb-mount/blob/master/requirements.yml)

## Installation

```
$ ansible-galaxy role install escalate.smb_mount
```

## Example Playbook

```
- hosts: all
  roles:
    - role: escalate.smb_mount
      tags: smbmount
```

## License

MIT
