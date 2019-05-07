Vagrant.configure("2") do |config|
  config.vm.define vm_name1="vm1" do |node|
    node.vm.box = "denislavd/xenial64"
    node.vm.hostname = vm_name1
    node.vm.network "private_network", ip: "192.168.56.56"
    node.vm.provider "virtualbox" do |vb|
      vb.memory = "2048"
      vb.cpus = 2
    end
  end
end
