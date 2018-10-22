# This repo is about how to make nginx docker container

1. Fork the repo
2. install Vagrant
3. `vagrant up`
4. `vagrant ssh`
5. `docker login` (submit login/pass )
6. `cd /vagrant`
7. edit dockernginx.json file to fit your credentials
8. `sudo packer build dockernginx.json`

# Test docker container

### Prerequisites - run below commands in order to set up the environment needed for the testing part
- **Install kitchen and dependencies**
  -  brew install rbenv
  -  rbenv install 2.3.1
  -  install chefdk 2.5.3-1 version
  -  gem install inspec
  -  gem install kitchen-test
  -  gem install kitchen-docker
  -  gem install bundler
  -  kitchen init --driver=docker --crete-gemfile
  -  bundle install
  
### Start your test:
`kitchen test` or `bundle exec kitchen-test`
