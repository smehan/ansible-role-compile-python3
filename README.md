# Ansible Role: Compile Python3

Fetches a specified Python source tarball, installs it into a specified build directory,
installs required dependencies, configures, makes and installs the resulting python3.

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

## Author Information

This role was created in 2017 by [Shawn Mehan](https://www.shawnmehan.com).