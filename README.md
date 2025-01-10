## msodbcsql

[![CI](https://github.com/Oefenweb/ansible-msodbcsql/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-msodbcsql/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-git--lfs-blue.svg)](https://galaxy.ansible.com/Oefenweb/msodbcsql)

Set up [Microsoft ODBC](https://learn.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-ver16) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)
* `wget` (will be installed)

#### Variables

* `msodbcsql_version`: [default: `18`]: Version to install (e.g. `17`)
* `msodbcsql_install`: [default: `[]`]: Additional packages to install (e.g. `mssql-tools`)

## Dependencies

None

## Recommended

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.msodbcsql
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-msodbcsql/issues)!
