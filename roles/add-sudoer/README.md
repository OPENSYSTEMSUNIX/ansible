# add-sudoers

### variables

| variable | value| required | comment |
|----------|------|----------|---------|
| `sudoers_cfg_file:` | /etc/sudoers | yes | |
| `sudoers_dropin_dir:` | /etc/sudoers.d | yes | |
| `sudo_file_name:` | "ansible-sudoers" | yes | name of drop in file |
| `sudoers_groups:` | -"%aix_admins"  <br> -random_user | yes | array of users or groups to add - groups must be quoted and start with a %  |
