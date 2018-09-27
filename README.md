# This repo is about how to make nginx docker container

1. Fork the repo
2. install Vagrant
3. vagrant up (yours or mine Vbox)
4. vagrant ssh and navigate to /vagrant shared folder
5. docker login (login with your credentials)
6. sudo packer build dockernginx.json (after you have edited the information for your docker repo in the json file)
