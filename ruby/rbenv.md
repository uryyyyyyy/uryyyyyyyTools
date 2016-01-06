
```
# clone
git clone https://github.com/rbenv/rbenv.git ~/.rbenv

# speed up
cd ~/.rbenv && src/configure && make -C src

# terminal
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile

# can use rbenv install
git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build

# check
rbenv install --list

# install
rbenv install 2.2.4

# set default
rbenv global 2.2.2

#check
ruby -v
```


