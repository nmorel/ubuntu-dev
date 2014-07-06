ubuntu-dev
==========

Files to setup development environment on Ubuntu using chef-solo and Berkshelf

Setup chef
====
Two solutions :
* Install the [chef-dk](http://www.getchef.com/downloads/chef-dk/linux/)

OR

* Install ruby and the chef + berkshelf gems :
```sh
# Install chef-solo
sudo ./install_chef_solo.sh

# install berkshelf
sudo gem install berkshelf
```

Running chef
===
```sh
# download cookbooks
berks vendor cookbooks

# install packages
sudo chef-solo -c solo.rb
```
