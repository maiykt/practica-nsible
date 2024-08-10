Vagrant.configure("2") do |config|
  config.vm.define "server1" do |server|
    server.vm.box = "ubuntu/bionic64"
    server.vm.hostname = "server1"
    server.vm.network "private_network", type: "dhcp"
    server.vm.provider "virtualbox" do |vb|
      vb.memory = "256"
      vb.cpus = 1
    end
    # server.ssh.insert_key = false  # Comentado para permitir la inserción automática de clave
  end

  config.vm.define "server2" do |server|
    server.vm.box = "ubuntu/bionic64"
    server.vm.hostname = "server2"
    server.vm.network "private_network", type: "dhcp"
    server.vm.provider "virtualbox" do |vb|
      vb.memory = "256"
      vb.cpus = 1
    end
    # server.ssh.insert_key = false  # Comentado para permitir la inserción automática de clave
  end

  config.vm.define "server3" do |server|
    server.vm.box = "ubuntu/bionic64"
    server.vm.hostname = "server3"
    server.vm.network "private_network", type: "dhcp"
    server.vm.provider "virtualbox" do |vb|
      vb.memory = "256"
      vb.cpus = 1
    end
    # server.ssh.insert_key = false  # Comentado para permitir la inserción automática de clave
  end
end
