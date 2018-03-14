# add-user-w-pw

Update the root password with the supplied value.

### Variables
| vaiable | value | required | comment |
|---------|-------|----------| --------|
| `au_password:`| "$6$rounds=656000$NdiU.....g0JeWZKj50" | no | |
| `au_name:` | *< username >* | yes | |
| `au_shell:` | /bin/bash | no | default shell |
| `au_comment:` | "user comment" | yes | |
| `au_optgroup:` | *< secondary group >* | no | secondary group to add user to on solaris and aix |

### how to generate passwords

* `$ sudo pip install passlib` 
* `$ python -c "from passlib.hash import sha512_crypt; import getpass; print sha512_crypt.encrypt(getpass.getpass())"` 
* Enter the password when prompted. The output will be a hash that is usable for the password varible.

