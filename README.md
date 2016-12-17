# Ansible Role: Veeam Agent

## Description

Install and Configure Veeam Agent for linux on Debian and CentOS.

## Installation

```
$ ansible-galaxy install sbaerlocher.veeam-agent
```

## Requirements

None

## Role Variables

```yml
veeam:
  vbrserver:
    name:
    endpoint:
    login:
    domain:
    password:
  repo:
    name: 
    path: 
  job:
    name:
    repo: 
    restopoints: 
    day:
    at: 
```

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.veeam-agent
```

## Changelog

### 1.0

* initial release

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2016, Simon Bärlocher