# roles readme

## name spaces
Each role should have it's own name space to prevent over riding. The name space is prepended to the beginnging of the variable names for the roles. *This conversion is still in process...*

### add-sudoers
| namespace | example |
|-----------|---------|
| `sudo_` | sudoers_cfg_file |

### add-user
| namespace |example |
|-----------|--------|
| `usr_` | usr_name |

### copy-sshkey
| namespace |example |
|-----------|--------|
| `Key_` | key_user|

### powerbroker
| namespace |example |
|-----------|--------|
| `pb_` | pb_ou |
