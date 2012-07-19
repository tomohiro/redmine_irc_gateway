Redmine IRC Gateway
================================================================================

[![Dependency Status](https://gemnasium.com/Tomohiro/redmine_irc_gateway.png)](https://gemnasium.com/Tomohiro/redmine_irc_gateway)
[![Build Status](https://secure.travis-ci.org/Tomohiro/redmine_irc_gateway.png)](https://secure.travis-ci.org/Tomohiro/redmine_irc_gateway)
[![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/Tomohiro/redmine_irc_gateway)

---

Overview
-------------------------------------------------------------------------------

### What's this?

This project provides an access to Redmine API via IRC Gateway.


Installation
-------------------------------------------------------------------------------

### Requirements

- Ruby 1.9.2+
- RubyGems
    - Rake
    - Bundler


### Create development environment

1. Clone Git repository

        $ git clone git@github.com:Tomohiro/redmine_irc_gateway.git
        $ cd redmine_irc_gateway

2. Installing RubyGems

    Bundler

        $ bundle install --path vendor/bundle



How to use
-------------------------------------------------------------------------------

### Make configuration file

Rename configuration file

    $ mv config/config.yml.example config/config.yml

or

    $ mkdir ~/.rig
    $ mv config/config.yml.example ~/.rig/config.yml

Edit config/config.yml or $HOME/.rig/config.yml. See `config/config.yml.example`.


### Run

#### Start

    $ bundle exec rig

#### Debug mode

    $ bundle exec rig --debug


### Cleaning environment

    $ rake clean


IRC Channel
-------------------------------------------------------------------------------

`#rig` at Freenode.net


Author
-------------------------------------------------------------------------------

- Tomohiro, TAIRA [@Tomohiro](http://twitter.com/Tomohiro)


Contributors
-------------------------------------------------------------------------------

- Naoto, SHINGAKI [@naotos](http://twitter.com/naotos)
- Yusaku, ONO [@yono](http://twitter.com/yono)



---

LICENSE
--------------------------------------------------------------------------------

&copy; 2012 Tomohiro, TAIRA.
This project is licensed under the MIT license.
See LICENSE for details.
