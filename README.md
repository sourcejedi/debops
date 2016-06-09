## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) php

[![Travis CI](http://img.shields.io/travis/debops/ansible-php.svg?style=flat)](http://travis-ci.org/debops/ansible-php) [![test-suite](http://img.shields.io/badge/test--suite-ansible--php-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-php/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.php5-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1585)

This role can be used as a dependency of other roles to easily enable
support for PHP7 or PHP5 on a host. `php*-fpm` package will be used as a backend
for PHP7/5 applications. This role works very well with `debops.nginx` role
for setting up `nginx` webserver as a frontend.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.php

### Documentation

More information about `debops.php` can be found in the
[official debops.php documentation](http://docs.debops.org/en/latest/ansible/roles/debops.php.html).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`php` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
