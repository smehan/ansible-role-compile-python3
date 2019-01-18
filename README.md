# Ansible Role: Compile Python3

Fetches a specified Python source tarball, installs it into a specified build directory,
installs required dependencies, configures, makes and installs the resulting python3.
Currently it defaults to Python 3.7.2 if none is specified.

[![Build Status](https://travis-ci.org/smehan/ansible-role-compile-python3.svg?branch=master)](https://travis-ci.org/smehan/ansible-role-compile-python3)

## Requirements

None.

## Role Variables

See [defaults/main.yml](defaults/main.yml)

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
         - { role: smehan.compile-python3 }

## License

MIT

## Contributions

To contribute please see [Contributing](CONTRIBUTING.md)

Contributers to date are as follows:

- pythonninja (fork deleted before I processed PR, constitutes bulk of 1-5-0)

## Author Information

This role was created in 2017 by [Shawn Mehan](https://www.shawnmehan.com).

