# nsswitch.conf template

# variables

| variable | value| required | comment |
|----------|------|----------|---------|
| `ns_conf_dir:` | yes | /etc |
| `ns_conf_file:` | yes | nsswitch.conf |
| `ns_perms:` | 644 | yes |
| `ns_passwd:` | - lsass <br> - sss <br> - files | yes |
| `ns_group:` | - lsass <br> - sss <br> - files | yes |
| `ns_shadow:` | - sss <br> - files | yes |
| `ns_hosts:` |  - dns <br> - files | yes |
