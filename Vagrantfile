Vagrant.configure("2") do |config|
  config.vm.box = "aakulov/bionic64"
  config.vm.hostname = "ptfeinteractive"
  config.vm.network "private_network", ip: "192.168.56.33"
  # config.vm.disk :disk, size: "60GB", primary: true

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024 * 4
    v.cpus = 2
  end
end
