# harlandclarke.local pbis install

Ansible playbook for deploying PowerBroker Identity Services (PBIS) Open Edition for Enterprise Linux

### Open PBIS Repo

* `Redhat Repo:` [http://repo.pbis.beyondtrust.com/yum.html](http://repo.pbis.beyondtrust.com/yum.html)

### Variables

| variable | value|
|----------|------|
| `pb_username:` | domain user with granted add/remove computers to the domain  | 
| `pb_password:` | password |
| `pb_domain_fqdn:` | Full qualified domain name of your domain |
| `pb_domain_netbios:` | NetBIOS domain name |
| `pb_homedir_template:` | homedir to be created for logging in users |
| `pb_login_shell_template:` | Login shell to be used for remote users |
| `pb_assume_default_domain:` | Sets the domain as default so users can login without DOMAIN\\ |
| `pb_require_membership_of:` | List of domain groups for allowed access |
| `pb_space_replacement:` | Configure the character to replace spaces |
| `pb_ou:` | Name of the OU to store the computer object |
| `pb_config_path:` | /tmp |
| `pb_config_file:` | pb_dump |

### todo

create service account for domain joins
