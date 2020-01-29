# Openstackclient
Step for setting up Openstack CLI in Ubuntu 18.4
OS = Ubuntu 18.04
Prerequisite for Openstack CLI 
# apt install virtualenv python-dev gcc python
# su - <user>
$ virtualenv openstack
$ source openstack/bin/activate  (if you face any issue try to do this as root)
(openstack) user@ubuntu:~$ pip install python-openstackclient
(openstack) praveen@DevOps:~$ openstack --version
openstack 4.0.0
 
