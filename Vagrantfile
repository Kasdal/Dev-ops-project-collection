Vagrant.configure("2") do |config|

    # Setting for the virtual machine we will be utilizing, in this case it will be ubuntu.
    config.vm.box = "bento/ubuntu-18.04"
    
    # Provider of the virtual enviroment, here we are using virtualbox by Oracle.
    config.vm.provider "virtualbox" do |vb|
    end
    # Network configuration. In our case we are using private network.

    config.vm.network "private_network", ip: "192.168.56.10"
  
    # Sync folder 
    config.vm.synced_folder ".", "/usr/share/nginx/html"
  
    # Shell provisioning. Once the server is created it will run serverscript.sh shell which will update the host and install and start nginx.
    config.vm.provision "shell", path: "serverscript.sh"
  
  end