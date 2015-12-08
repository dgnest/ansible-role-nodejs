# Ansible Role Nodejs

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-nodejs.svg)](https://travis-ci.org/hadenlabs/ansible-role-nodejs)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-nodejs.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-nodejs)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-nodejs.svg)](https://github.com/hadenlabs/ansible-role-nodejs/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [nodejs][link-nodejs] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - [Homebrew][link-brew] must be installed.


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for tmux
    tmux_install_latest: true
    # tmux_version:  ## This is not defined by default

If you want to install a specific version, set `tmux_install_latest: false` and `tmux_version` to the version you want.

## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - nodejs

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.nodejs }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-author]
- [All Contributors][link-contributors]

[link-nodejs]: https://nodejs.org/en/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: contributors
