# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.network "private_network", ip: "192.168.56.19"
  config.vm.synced_folder "./app/", "/var/www/html"
  config.vm.provision :shell, path: "bootstrap.sh"
end
