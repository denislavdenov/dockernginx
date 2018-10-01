# This repo is about how to make nginx docker container

1. Fork the repo
2. install Vagrant
3. `vagrant up`
4. `vagrant ssh`
5. `docker login` (submit login/pass )
6. `cd /vagrant`
7. edit dockernginx.json file to fit your credentials
8. `sudo packer build dockernginx.json`

## TODO

Update dockernginx.json to use variables
