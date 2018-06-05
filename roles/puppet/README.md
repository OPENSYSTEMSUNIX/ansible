# Install and configure the puppet agent

role to install and config the puppet agent for Enterprise Linux

## Variables

| variable | value | required | comment |
|---------|-------|----------| --------|
| `ppt_host:` | "sa1-nim-p1.harlandclarke.local" | yes | default value for nim host |
| `ppt_key:` | "http://sa1x-spacewalk-p1/pub/gpg/RPM-GPG-KEY-lparkey" | yes | default value for the rpm gpg key|
| `ppt_ca_host:` | "puppetca.harlandclarke.local" | yes | puppet CA host |
