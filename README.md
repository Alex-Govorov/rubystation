# Rubystation

Notes what should help me in next RoR instalation on new system

1. Ставим Ubuntu

2. Накатываем https://rvm.io/ и последнею версию ruby, затем rubocop

rvm list known - посмотреть какие версии можно установить

rvm install 2.2(например)

rvm list - посмотреть какие установлены

rvm use 2.2.1 --default - использовать версию по умолчанию

3. Ставим Sublime Text, к нему модуль SyncSetting , синхронизируемся с gist

4. Качаем с github'a настройки rubocop

# Установква Rails
1. Устанавливаем yarn + Node.js

https://classic.yarnpkg.com/en/docs/install#debian-stable

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

sudo apt update

sudo apt install yarn

2. Устанавливаем rails

gem install rails
