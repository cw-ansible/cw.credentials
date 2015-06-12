<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.credentials.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.credentials)
[![Tweet this](http://img.shields.io/badge/Tweet-it00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw.credentials&text=)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# Credentials

Manage users and access on a machine.

## Usage

Include the `cw.ansible-bootstrap` module to your playbook.


## Requirement

This role requires the `match_hosts` filter from
[cw-ansible/filter_plugins](https://github.com/cw-ansible/filter_plugins)
and the `subelements_safe` lookup from
[cw-ansible/lookup_plugins](https://github.com/cw-ansible/lookup_plugins).


## Description

This roles manages groups, users, *SSH* keys and *sudo* permissions.


## Configuration

See specific documentation in `defaults/main.yml`



## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
