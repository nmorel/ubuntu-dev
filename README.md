ubuntu-dev
==========

Files to setup development environment on Ubuntu using chef-solo and librarian-chef

```sh
# Install chef-solo
sudo ./install_chef_solo.sh

# install librarian-chef
sudo gem install librarian-chef

# download cookbooks
librarian-chef install

# install packages
sudo chef-solo -c solo.rb
```
