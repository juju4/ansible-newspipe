[![Actions Status - Master](https://github.com/juju4/ansible-newspipe/workflows/AnsibleCI/badge.svg)](https://github.com/juju4/ansible-newspipe/actions?query=branch%3Amaster)
[![Actions Status - Devel](https://github.com/juju4/ansible-newspipe/workflows/AnsibleCI/badge.svg?branch=devel)](https://github.com/juju4/ansible-newspipe/actions?query=branch%3Adevel)

# newspipe ansible role

Ansible role to setup [newspipe](https://github.com/cedricbonhomme/newspipe)

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 2.17

### Operating systems

Tested on Ubuntu 24.04, 22.04, 20.04, Centos/Rockylinux 9.

## Example Playbook

Just include this role in your list.
For example

```
- host: myhost
  roles:
    - juju4.newspipe
```

you probably want to review variables

## Variables

N/A

## Continuous integration

```
$ pip install molecule docker
$ molecule test
$ MOLECULE_DISTRO=ubuntu:24.04 molecule test --destroy=never
```

## Troubleshooting & Known issues

N/A

## License

BSD 2-clause
