# add-sudoers

### variables

| variable | value|
|----------|------|
| `sudoers_cfg_file:` | /etc/sudoers |
| `sudoers_dropin_dir:` | /etc/sudoers.d |
| `sudoers_file:` | "ansible-sudoers" # name of drop in file |
| `sudoers_groups:` | # array of users or groups to add - groups must be quoted and start with a % <br> - "%aix_admins" <br> - random_user |
