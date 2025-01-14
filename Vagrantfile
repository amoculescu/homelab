Vagrant.configure("2") do |config|
  config.vm.box = "/home/andrei/Downloads/CentOS-Stream-Vagrant-10-20250113.0.x86_64.vagrant-libvirt.box"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yaml"
  end
end
