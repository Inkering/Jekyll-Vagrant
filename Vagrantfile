Vagrant.configure("2") do |config|
	config.vm.box = "ubuntu/xenial64"
  config.vm.hostname = "jekyll"
	config.vm.network "forwarded_port", guest: 4000, host: 4000
	config.vm.provision "shell", path: "bootstrap.sh"
	config.ssh.forward_agent = true
end