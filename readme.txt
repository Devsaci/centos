# Command lunix
$ vagrant init eurolinux-vagrant/centos-stream-9
$ cat Vagrantfile 
$ vagrant up
$ vagrant status
Current machine states:

default                   running (virtualbox)

The VM is running. To stop this VM, you can run `vagrant halt` to  
shut it down forcefully, or you can run `vagrant suspend` to simply
suspend the virtual machine. In either case, to restart it again,  
simply run `vagrant up`.

$ vagrant ssh
This box was generated by EuroLinux

Any suggestions are welcome at https://github.com/EuroLinux/cloud-images-rfc/

Happy using.
To delete this message use:
echo '' > /etc/motd
[vagrant@localhost ~]$ 

[vagrant@localhost ~]$ whoami
vagrant

[vagrant@localhost ~]$ pwd
/home/vagrant

[vagrant@localhost ~]$ sudo -i
[root@localhost ~]# 

[root@localhost ~]# whoami
root

[root@localhost ~]# exit
logout
[vagrant@localhost ~]$

[vagrant@localhost ~]$ exit
logout

sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)
$

sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)
$ vagrant halt
==> default: Attempting graceful shutdown of VM...

sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)
$ vagrant box list
eurolinux-vagrant/centos-stream-9 (virtualbox, 9.0.31)

sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)
$ cd /d/vagrant-vms/ubuntu

sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)
$ cd centos

sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)
$ ls -a
./  ../  .git/  .vagrant/  readme.txt  Vagrantfile
sacid@Gen□ve MINGW64 /d/vagrant-vms/centos (main)       
$ ls ~/.vagrant.d/
boxes/  gems/                 rgloader/      tmp/
data/   insecure_private_key  setup_version