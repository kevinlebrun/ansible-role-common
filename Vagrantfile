# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
    config.vm.box = "debian-7.2.0-x86_64"
    config.vm.box_url = "https://dl.dropboxusercontent.com/u/17664745/debian-7.2.0-x86_64.box"

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "tests/test.yml"
        ansible.sudo = true
    end
end
