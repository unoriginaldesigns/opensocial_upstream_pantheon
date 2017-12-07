# -*- mode: ruby -*-
# vi: set ft=ruby :

ENV['DRUPALVM_PROJECT_ROOT'] = "#{__dir__}"
ENV['DRUPALVM_CONFIG_DIR'] = "."
ENV['DRUPALVM_DIR'] = "../drupal-vm"

# Load the real Vagrantfile
load "#{__dir__}/#{ENV['DRUPALVM_DIR']}/Vagrantfile"

Vagrant.configure('2') do |config|
  config.ssh.private_key_path = ["~/.vagrant.d/insecure_private_key","~/.ssh/id_rsa"]
  config.ssh.forward_agent = true
end
