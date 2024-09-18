# -*- mode: ruby -*-
# vi: set ft=ruby :

#mv1
Vagrant.configure("2") do |config|
	config.vm.define "mv1" do |mv1|
		#nom d'hôte
		mv1.vm.hostname = "mv1"
		mv1.vm.box = "generic/ubuntu2004"
		
		#memoire et cpu
		mv1.vm.provider "virtualbox" do |vb|
			vb.memory = "2048"
			vb.cpus = 2
		end
		mv1.vm.network "private_network", type: "static", ip: "192.168.56.10"
	end

#mv2
	config.vm.define "mv2" do |mv2|
		#nom d'hôte
		mv2.vm.hostname = "mv2"
		mv2.vm.box = "generic/ubuntu2004"
	
		#memoire et cpu
		mv2.vm.provider "virtualbox" do |vb|
			vb.memory = "2048"
			vb.cpus = 2
		end
		mv2.vm.network "private_network", type: "static", ip: "192.168.56.11"

	end

#mv3
	config.vm.define "mv3" do |mv3|
		#nom d'hôte
		mv3.vm.hostname = "mv3"
		mv3.vm.box = "generic/ubuntu2004"
	
		#memoire et cpu
		mv3.vm.provider "virtualbox" do |vb|
			vb.memory = "2048"
			vb.cpus = 2
		end
		mv3.vm.network "private_network", type: "static", ip: "192.168.56.12"
	end
end
