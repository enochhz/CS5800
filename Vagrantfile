Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-16.04"
  config.vm.network "forwarded_port", guest: 8080, host: 8000, host_ip: "127.0.0.1"
end
