Vagrant.configure(2) do |config|
    config.vm.box = "geerlingguy/ubuntu1804"
    config.vm.provider "virtualbox" do |v|
        v.name = "hardening-demo"
        v.memory = 1024
        v.cpus = 2
    end
    config.vm.hostname = "hardening-demo"
    config.vm.network :private_network, ip: "192.168.33.7"
    config.ssh.insert_key = false
end