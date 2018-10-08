# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  #Identify which Vagrant box to use 
  config.vm.box = "centos/7"
  
  config.vm.define "workstation" do |server|
    # Define host settings
    server.vm.hostname = "workstation.lab.example.com"
    server.vm.network :private_network, ip: "192.168.33.10"
    
    # Define sync folders

    # Define shell provisioner
    
    # Define ansible provisioner
    server.vm.provision "ansible" do |ansible|
      ansible.playbook = "playbook.yml"
    end
  end
  
  config.vm.define "servera" do |server|
    # Define host settings
    server.vm.hostname = "servera.lab.example.com"
    server.vm.network :private_network, ip: "192.168.33.11"
    
    # Define sync folders

    # Define shell provisioner

    # Define ansible provisioner
    server.vm.provision "ansible" do |ansible|
      ansible.playbook = "playbook-target.yml"
    end
  end
  
  config.vm.define "serverb" do |server|
    # Define host settings
    server.vm.hostname = "serverb.lab.example.com"
    server.vm.network :private_network, ip: "192.168.33.12"
    
    # Define sync folders

    # Define shell provisioner

    # Define ansible provisioner
    server.vm.provision "ansible" do |ansible|
      ansible.playbook = "playbook-target.yml"
    end
  end
  
  config.vm.define "serverc" do |server|
    # Define host settings
    server.vm.hostname = "serverc.lab.example.com"
    server.vm.network :private_network, ip: "192.168.33.13"
    
    # Define sync folders

    # Define shell provisioner

    # Define ansible provisioner
    server.vm.provision "ansible" do |ansible|
      ansible.playbook = "playbook-target.yml"
    end
  end


end

