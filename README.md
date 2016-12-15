ilpianista.nanoc
================

[![Build Status](https://travis-ci.org/ilpianista/ansible-role-nanoc.svg?branch=master)](https://travis-ci.org/ilpianista/ansible-role-nanoc)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-nanoc-blue.svg)](https://galaxy.ansible.com/ilpianista/nanoc/)

Installs [nanoc](https://nanoc.ws/about/).

Requirements
------------

Ruby >= 2.1.0

Git when `from_source` is set to `True`.

Role Variables
--------------

Available variables are listed below, along with default values (see [defaults/main.yml](defaults/main.yml)):

    user_install: True

Installs `nanoc` for `ansible_user` only.

    pre_release: False

Allow installation of pre-release versions of the gem.

    from_source: False

Builds `nanoc` from sources.

Example Playbook
----------------

    - hosts: all
      roles:
         - ilpianista.nanoc

License
-------

BSD

Author Information
------------------

This role was created by [Andrea Scarpino](https://andreascarpino.it).
