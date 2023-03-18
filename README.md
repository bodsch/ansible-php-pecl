
# Ansible Role:  `php-pecl`

Ansible role to install php pecl packages on various systems.

Detect available PHP Version based on `php_version` Variable.

Supports PHP version 7 and 8, **as long as the corresponding versions are available.**

ArchLinux has removed the PHP 7 packages from their repository!

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/bodsch/ansible-php-pecl/main.yml?branch=main)][ci]
[![GitHub issues](https://img.shields.io/github/issues/bodsch/ansible-php-pecl)][issues]
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bodsch/ansible-php-pecl)][releases]
[![Ansible Quality Score](https://img.shields.io/ansible/quality/50067?label=role%20quality)][quality]

[ci]: https://github.com/bodsch/ansible-php-pecl/actions
[issues]: https://github.com/bodsch/ansible-php-pecl/issues?q=is%3Aopen+is%3Aissue
[releases]: https://github.com/bodsch/ansible-php-pecl/releases
[quality]: https://galaxy.ansible.com/bodsch/php-pecl

## Requirements & Dependencies

### Operating systems

Tested on

* ArchLinux (**only PHP 8!**)
* Debian based
    - Debian 10 / 11
    - Ubuntu 20.04

## usage

```yaml

```

## Contribution

Please read [Contribution](CONTRIBUTING.md)

## Development,  Branches (Git Tags)

The `master` Branch is my *Working Horse* includes the "latest, hot shit" and can be complete broken!

If you want to use something stable, please use a [Tagged Version](https://github.com/bodsch/ansible-php-pecl/tags)!


## Author

- Bodo Schulz

## License

[Apache](LICENSE)

**FREE SOFTWARE, HELL YEAH!**
