beanstalkd-deb
===============

Ant script for generating a deb package for beanstalkd on Ubuntu.

##Dependencies:

You need:

-ant `(sudo apt-get install ant)`
-fpm `(sudo gem install fpm)`

##Generate a deb:

In setup folder run ant gen_deb and a .deb package will be generated in that folder.

In order to change the commit of beanstalkd you can change `bk.rev` inside `setup.properties`.

