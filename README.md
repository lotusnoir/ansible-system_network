# ansible-system_network

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_network-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_network)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_network.svg)](https://github.com/lotusnoir/ansible-system_network/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_network?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_network)
[![downloads](https://img.shields.io/ansible/role/d/56951)](https://galaxy.ansible.com/lotusnoir/system_network)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56951)](https://galaxy.ansible.com/lotusnoir/system_network)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Description](#description)
- [Requirements](#requirements)
- [Role variables](#role-variables)
- [Examples](#examples)
- [License](#license)
- [Author Information](#author-information)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Configure network interfaces
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_network
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_network


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
