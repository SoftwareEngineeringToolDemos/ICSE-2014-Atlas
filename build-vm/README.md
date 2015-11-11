Details on vm built using Vagrant
------

Environment
------
__Virtual Box used:__ [ubuntu/trusty32](https://atlas.hashicorp.com/ubuntu/boxes/trusty32)

Folder content
-----
This build-vm folder contains following things:
- __README.md file__
- __Vagrantfile__
  This is the script (& configuration) file of the VM.


Steps to create a VM using this build
-----

1. Download [Vagrant](https://www.vagrantup.com/)
2. Install Vagrant
3. Download [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
4. Install VirtualBox
5. Download all files from [build-vm](https://github.com/SoftwareEngineeringToolDemos/ICSE-2014-Atlas/tree/master/build-vm) to local machine.
6. Open a command line/teminal window and go to build-vm folder
7. Run "__vagrant up__"
8. In VirtualBox GUI, enter credentials for username: __vagrant__. Password: __vagrant__

Note:

Please wait until "__vagrant up__" finishes execution before working on GUI.


Reference
-----
1. http://askubuntu.com/questions/56104/how-can-i-install-sun-oracles-proprietary-java-jdk-6-7-8-or-jre
2. https://www.gaggl.com/2013/06/quick-manual-eclipse-install-on-ubuntu/
3. http://aruizca.com/steps-to-create-a-vagrant-base-box-with-ubuntu-14-04-desktop-gui-and-virtualbox/
4. https://github.com/ljdursi/hadoop-for-hpcers-tutorial/blob/master/vm-cfg/gui/Vagrantfile
5. http://askubuntu.com/questions/53822/how-do-you-run-ubuntu-server-with-a-gui
6. http://serverfault.com/questions/500764/dpkg-reconfigure-unable-to-re-open-stdin-no-file-or-directory
7. https://docs.vagrantup.com/v2/getting-started/
