# roles

### ansible roles

## name spaces
Each role should have it's own name space to prevent over riding. The name space is prepended to the beginnging of the variable names for the roles. *This conversion is still in process...*

### add-sudoers
| namespace | example |
|-----------|---------|
| `sudo` | sudoers_cfg_file |

### add-user
| namespace |example |
|-----------|--------|
| `usr_` | usr_name |

### copy-sshkey
| namespace |example |
|-----------|--------|
| `key_` | key_user|

### powerbroker
| namespace |example |
|-----------|--------|
| `pb_` | pb_ou |

### dir tree

```
.
├── foreman.py
├── playbooks
│   ├── add-user-w-key.yaml
│   ├── install-powerbroker.yaml
│   └── roles -> ../roles/
├── README.md
└── roles
    ├── add-sudoer
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yaml
    │   └── templates
    │       └── nopasswd.j2
    ├── add-user
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── handlers
    │   │   └── main.yaml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yaml
    │   └── templates
    │       └── nopasswd.j2
    ├── common
    │   ├── defaults
    │   │   └── main.yml
    │   ├── handlers
    │   │   └── main.yml
    │   ├── meta
    │   │   └── main.yml
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   ├── tests
    │   │   ├── inventory
    │   │   └── test.yml
    │   └── vars
    │       └── main.yml
    ├── copy-sshkey
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── README.md
    │   └── tasks
    │       └── main.yaml
    ├── powerbroker
    │   ├── defaults
    │   │   └── main.yaml
    │   ├── handlers
    │   │   └── main.yaml
    │   ├── README.md
    │   └── tasks
    │       └── main.yaml
    └── README.md
```
