# sysdev
System programming.

## Virtual Machine Setup

Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html). Confirm that they were installed properly by running the following commands.

```
vboxmanage --version
vagrant --version
```

Do not delete the Vagrantfile in the repo. Below are vagrant commands.

```
vagrant init             # create a new VM
vagrant up               # turn on VM
vagrant ssh              # connect to the VM
exit                     # exit ssh; call within your vm terminal (VM is still on)
vagrant halt             # turns off your VM
```

 `cd` into the repo directory and create a new vagrant environment. Then, you can turn it on and connect to it.

To `cd` straight into `/vagrant` after connecting, you can add `cd /vagrant` as the last line to `.profile` file in `/home/vagrant`.

Run below commands to install packages for the project.

```
sudo apt install build-essential
sudo apt install clang
sudo apt install clang-format
sudo apt install gdb
```

## Project Components

WeensyOS



