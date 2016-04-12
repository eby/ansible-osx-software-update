# ansible-osx-software-update

Ansible role that rununs the OSX softwareupdate program to update the OS and apps.

[![Build Status](https://travis-ci.org/osxstrap/ansible-osx-software-update.svg?branch=master)](https://travis-ci.org/osxstrap/ansible-osx-software-update)

## Requirements

## Role Variables

Available variables are listed below, along with default values:

    osx_update_install: True
    osx_update_recommended_only: True
    osx_update_download_only: False

## Dependencies

## Example Playbook

    - hosts: all
      roles:
        - { role: jeremyltn.osx-software-update }

## License

MIT
