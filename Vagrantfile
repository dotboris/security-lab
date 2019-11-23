# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure('2') do |config|
  config.vm.netowrk 'private_network', type: 'dhcp'

  config.vm.define 'metasploitable:ubuntu' do |config|
    config.vm.box = 'rapid7/metasploitable3-ub1404'
  end

  config.vm.define 'metasploitable:windows' do |config|
    config.vm.box = 'rapid7/metasploitable3-win2k8'
  end

  config.vm.define 'kali' do |config|
    config.vm.box = 'kalilinux/rolling'
  end
end
