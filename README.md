beanstalkd-deb
===============

ANT script for generating a DEB package for [Beanstalkd][1] on Ubuntu.

##Dependencies:

You need:

- ant `(sudo apt-get install ant)`
- fpm `(sudo gem install fpm)`

##Generate a deb:

In setup folder run `ant make_deb` and a DEB package will be generated in that folder.

In order to change the commit of Beanstalkd you can change `bk.rev` inside `setup.properties`.

[1]:https://github.com/kr/beanstalkd