Vagrant.configure("2") do |config|
	config.vm.define "prod" do |prod|
		prod.vm.box = "ubuntu/trusty64"
    prod.vm.hostname = 'prod'
    prod.vm.box_url = "ubuntu/trusty64"
		prod.vm.network :private_network, ip: "192.168.3.33"
	end

  config.vm.define "dev" do |dev|
    dev.vm.box = "ubuntu/trusty64"
    dev.vm.hostname = 'dev'
    dev.vm.box_url = "ubuntu/trusty64"
		dev.vm.network :private_network, ip: "192.168.3.34"
 	end



end
