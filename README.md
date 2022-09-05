This is the repo for https://app.vagrantup.com/coderhs/boxes/ubuntu-22-04-docker


How to use box

```rb
Vagrant.configure("2") do |config|
  config.vm.box = "coderhs/ubuntu-22-04-docker"
  config.vm.box_version = "1.0.0"
end
```
