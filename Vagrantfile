Vagrant.configure("2") do |config|
  config.vm.box = "denislavd/xenial64"
  config.vm.provision "shell", path: "scripts/provision.sh" , privileged: false
  config.vm.synced_folder ".", "/vagrant", disabled: false
end
