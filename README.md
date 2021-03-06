## import_pgp_public_keys

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](http://img.shields.io/travis/ypid/ansible-import_pgp_public_keys.svg?style=flat)](http://travis-ci.org/ypid/ansible-import_pgp_public_keys)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-ypid.import_pgp_public_keys-660198.svg?style=flat)](https://galaxy.ansible.com/detail#/role/4109)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](https://galaxy.ansible.com/detail#/role/4109)
[![GitHub Tags](https://img.shields.io/github/tag/ypid/ansible-import_pgp_public_keys.svg)](https://github.com/ypid/ansible-import_pgp_public_keys)
[![GitHub Stars](https://img.shields.io/github/stars/ypid/ansible-import_pgp_public_keys.svg)](https://github.com/ypid/ansible-import_pgp_public_keys)


Simple role to import OpenPGP public keys by key fingerprint.

Depends on `gpg` being installed which should be the default for all current Linux distributions.

### Installation

This role requires at least Ansible `v1.3`. To install it, run:

```Shell
ansible-galaxy install ypid.import_pgp_public_keys
```

To install via git, run either:

```Shell
git clone https://github.com/ypid/ansible-import_pgp_public_keys.git ypid.import_pgp_public_keys
git submodule add https://github.com/ypid/ansible-import_pgp_public_keys.git ypid.import_pgp_public_keys
```



### Role variables

List of default variables available in the inventory:

```YAML
---

import_pgp_keys:
  root:
    - EF96BC32AC57CFC72DF01D8C489A4D5EC353C98A
    - EDE1371D1B87D28DA5E8051586FD980BBF1A40F8
    - C505B5C93B0DB3D338A1B6005FE92C12EE88E1F0

import_pgp_keys_group: {}
import_pgp_keys_host: {}
```




### Authors and license

`import_pgp_public_keys` role was written by:

- [Robin Schneider](http://ypid.de/) | [e-mail](mailto:ypid@riseup.net) | [Twitter](https://twitter.com/ypid) | [GitHub](https://github.com/ypid)

License: [AGPLv3](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-%28agpl-3.0%29)

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
