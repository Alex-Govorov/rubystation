# Rubystation

Notes what should help me in next RoR instalation on new system

## RVM
First step is installing [RVM](http://http://rvm.io/)
```bash
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

If you got timeout on this stage you can force to use port 80

```bash
gpg --keyserver hkp://keys.gnupg.net:80 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

```bash
\curl -sSL https://get.rvm.io | bash -s stable
```

Installing last ruby version: 2.5 on the moment.

```bash
rvm install 2.5 
```
