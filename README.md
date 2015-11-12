# YWW Vagrant/WP virtual machine #

## Instructions ##

1. Install [VCCW](http://vccw.cc/)

2. Clone this repository

3. Edit `site.yml` with basic site details (slug, domain, name)

4. Run the `./yww.sh` shell script which will automatically:

  * clone the [YWW WordPress development kit](https://bitbucket.org/yeswework/yww-wp-dev-kit) into a `dev` folder

  * activate the Vagrant virtual machine

  * install WordPress and our selected plugins (ACF, Timber, Sucuri, Query Monitor) in the virtual machine

  * add a line to the Hosts file for local access to the site while Vagrant is up

  * install all development and front-end dependencies via NPM and Bower

  * compile the site (with Gulp) for an initial run

  * activate the theme in WordPress

## What then? ##

Instructions on available gulp tasks can be found in the [dev kit readme](https://bitbucket.org/yeswework/yww-wp-dev-kit])