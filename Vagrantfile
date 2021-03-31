Vagrant.configure("2") do |config|

  config.vm.define "monitoring" do |monitoring|
    monitoring.vm.box = "centos/7"
    monitoring.vm.network "private_network", ip: "192.168.60.10"

  end

    config.vm.provision "ansible" do |ansible|
      ansible.playbook = "ansible/playbook.yml"

    end

end