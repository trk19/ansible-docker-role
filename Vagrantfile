Vagrant.configure("2") do |config|
  config.vm.define "webserver" do |webserver|

    webserver.vm.box = "ubuntu/focal64"

    webserver.vm.provider "virtualbox" do |vb|
      vb.memory = "1024"
      vb.cpus = 2
      vb.name = "webserver"
    end
    
    webserver.vm.network "public_network", bridge: "wlp3s0"
    
    webserver.vm.provision "ansible" do |ansible|
      ansible.playbook = "main.yml"
    end


  end
end
