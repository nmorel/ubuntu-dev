ubuntu-dev
==========

Files to setup development environment on Ubuntu using chef-solo and Berkshelf

```sh
# Install chef-solo
sudo ./install_chef_solo.sh

# install berkshelf
sudo gem install berkshelf

# download cookbooks
berks vendor cookbooks

# install packages
sudo chef-solo -c solo.rb
```
