Vagrant::Config.run do |config|
  config.vm.box = "preceise32"
  config.vm.box_url = "http://files.vagrantup.com/precise32.box"

  config.vm.provision :puppet do |puppet|
    puppet.manifests_path = "puppet/manifests"
    puppet.manifest_file  = "site.pp"
	puppet.module_path    = "puppet/modules"
  end
end
