# Ansible Role Nodejs

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-nodejs.svg)](https://travis-ci.org/dgnest/ansible-role-nodejs)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-nodejs.svg)](https://github.com/dgnest/ansible-role-nodejs/issues)
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
    # defaults file for nodejs
    nodejs_version: 0.12.7


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
         - { role: dgnest.nodejs }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].

- [All Contributors][link-contributors]

[link-nodejs]: https://nodejs.org/en/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS
[link-company]: https://github.com/dgnest
