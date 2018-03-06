# harlandclarke.local pbis install
====================

Ansible playbook for deploying PowerBroker Identity Services (PBIS) Open Edition for Enterprise Linux

## Open PBIS Repo
* `Redhat Repo:` [http://repo.pbis.beyondtrust.com/yum.html](http://repo.pbis.beyondtrust.com/yum.html)

## Variables
* `domain_user:` and `domain_pass:` of a domain user with granted add/remove computers to the domain
* `domain_fqdn:` Full qualified domain name of your domain
* `domain_netbios:` NetBIOS domain name
* `homedir_template:` homedir to be created for logging in users
* `login_shell_template:` Login shell to be used for remote users
* `assume_default_domain:` Sets the domain as default so users can login without DOMAIN\
* `require_membership_of:` List of domain groups for allowed access
