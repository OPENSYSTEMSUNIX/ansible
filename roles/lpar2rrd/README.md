# Install and configure the lpar2rrd agent

role to install and config the lpar2rrd agent for Enterprise Linux

### Lpar2rrd URL

* `lpar agent download:` http://www.lpar2rrd.com/download-xorux.htm?4.0

### Variables

| variable | value | required | comment |
|---------|-------|----------| --------|
| `lpar_host:`| "sa1-nim-p1.harlandclarke.local" | yes | default value for nim host |
| `lpar_key:` | "http://sa1x-spacewalk-p1/pub/gpg/RPM-GPG-KEY-lparkey" | yes | default value for the rpm gpg key|
