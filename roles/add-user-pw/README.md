# add-user-w-pw

Update the root password with the supplied value.

### Variables
| vaiable | vaule |
|---------|-------|
| `au_password:`| hash of password |
| `au_name:` | username |
| `au_shell:` | default shell (/bin/bash) |
| `au_comment:` | user comment |
| `au_optgroup:` | secondary group |

### how to generate passwords

* `$ sudo pip install passlib` 
* `$ python -c "from passlib.hash import sha512_crypt; import getpass; print sha512_crypt.encrypt(getpass.getpass())"` 
* Enter the password when prompted. The output will be a hash that is usable for the password varible.

