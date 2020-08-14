# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANT_API_VERSION = "2"

Vagrant.configure(VAGRANT_API_VERSION) do |config|
  config.vm.define "database" do |db|
    db.vm.box = "debian/contrib-buster64"
    db.vm.hostname = 'db01'
    db.vm.network "private_network", ip: "192.168.55.100"
  end

  config.vm.define "firewall" do |firewall|
    firewall.vm.box = "hashicorp/bionic64"
    firewall.vm.hostname = "firewall"
    firewall.vm.network "private_network",ip:"192.168.55.254"
    firewall.vm.network "public_network"
  end


end