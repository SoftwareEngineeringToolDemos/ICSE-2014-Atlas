Details on vm built using Vagrant
------

Environment
------
__Virtual Box used:__ [box-cutter/ubuntu1404-desktop](https://vagrantcloud.com/box-cutter/boxes/ubuntu1404-desktop)

Folder content
-----
This build-vm folder contains following things:
- [README.md](https://github.com/SoftwareEngineeringToolDemos/ICSE-2014-Atlas/blob/master/build-vm/README.md) -
  This files gives a brief idead of how to create, spin up and login into this VM.
- [Vagrantfile](https://github.com/SoftwareEngineeringToolDemos/ICSE-2014-Atlas/blob/master/build-vm/Vagrantfile) -
  This is the script (& configuration) file of the VM.
- [vm-files.tar.gz](https://github.com/SoftwareEngineeringToolDemos/ICSE-2014-Atlas/blob/master/build-vm/vm-files.tar.gz) -
  This zip file has all necessary desktop file (README.txt, license.txt, Installation.txt etc.,)

Steps to create a VM using this build
-----

1. Download [Vagrant](https://www.vagrantup.com/)
2. Install Vagrant
3. Download [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
4. Install VirtualBox
5. Download all files from [build-vm](https://github.com/SoftwareEngineeringToolDemos/ICSE-2014-Atlas/tree/master/build-vm) to local machine.
6. Open a command line/teminal window and go to build-vm folder
7. Run "__vagrant up__"
8. In VirtualBox GUI, if prompted for credentials, please enter username: __vagrant__. Password: __vagrant__

Note:

Please wait until "__vagrant up__" finishes execution before working on GUI.

***

* This script install Oracle JAVA 1.7.
* This script installs Eclipse Luna (4.4), installs tool plugin and points Eclipse to default workspace.
* This script copies all necessary files to Desktop. (README.txt, license.txt, Installation.txt, link to tool demo in youtube)
* This script also runs Eclipse (helps in using the tool) and gedit (to provide basic idea on how to work with the tool and necessary license information) on startup

***

References:
-----
1. http://askubuntu.com/questions/56104/how-can-i-install-sun-oracles-proprietary-java-jdk-6-7-8-or-jre
2. https://www.gaggl.com/2013/06/quick-manual-eclipse-install-on-ubuntu/
3. http://aruizca.com/steps-to-create-a-vagrant-base-box-with-ubuntu-14-04-desktop-gui-and-virtualbox/
4. https://github.com/ljdursi/hadoop-for-hpcers-tutorial/blob/master/vm-cfg/gui/Vagrantfile
5. http://askubuntu.com/questions/53822/how-do-you-run-ubuntu-server-with-a-gui
6. http://serverfault.com/questions/500764/dpkg-reconfigure-unable-to-re-open-stdin-no-file-or-directory
7. https://docs.vagrantup.com/v2/getting-started/
8. http://askubuntu.com/questions/159008/how-to-add-startup-applications-in-lubuntu
9. https://help.ubuntu.com/community/AutoLogin
10. http://askubuntu.com/questions/418407/how-do-i-create-a-desktop-file-to-launch-eclipse
