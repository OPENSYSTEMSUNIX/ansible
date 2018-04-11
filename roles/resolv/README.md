# resolv.conf template

## variables

| variable | value| required | comment |
|----------|------|----------|---------|
| `rs_conf_dir:` | /etc | yes |
| `rs_conf_file:` | resolv.conf | yes |
| `rs_perms:` | 644 | yes |
| `rs_search_doms:` | - domain1.com <br> - domain2.com | yes| takes an array |
| `rs_name_servers:` | - 8.8.8.8 <br> - 8.8.4.4 | yes | takes an array |

