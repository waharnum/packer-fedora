Vagrant.configure(2) do |config|
 config.vm.box = "fedora22-gnome"
 config.vm.provider "virtualbox" do |vb|
   vb.gui = true
   vb.customize ["modifyvm", :id, "--vram", "128"]
   vb.memory = 2048
   vb.cpus = 2
 end
end
