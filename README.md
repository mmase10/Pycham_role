# Pycham_role

## pycharm

Modified from: (https://travis-ci.org/Oefenweb/ansible-pycharm.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-pycharm)

Set up [PyCharm](https://www.jetbrains.com/pycharm/).

#### Requirements

Download Pycharm and place on Web Server for access

#### Variables


* pycharm_version: 2018.2
* pycharm_edition: community
* pycharm_install_prefix: /opt
* pycharm_execution_file: /bin/pycharm.sh
* pycharm_downloads_path: /var/lib/ansible/pycharm/downloads

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - pycharm_role
```

#### License

MIT

#### Author Information

mmase10

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/mmase10/Pycham_role/issues/new)!
