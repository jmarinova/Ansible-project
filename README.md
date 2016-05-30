# Ansible-project's READ ME

Task: create ansible playbook that will automate the installation of ansible on a Linux machine - Ubuntu 14.04

Steps to reproduce task:
- install ansible on my personal computer - Mac OS X 10.11.1
- install VirtualBox and a virtual machine - Ubuntu 14.04
- create ansible hosts file with single record describing targeted virtual machine
- generate SSH private+public key-pair on my local machine and exchange the public key with my virtual machine --> http://linuxsay.com/t/error-while-install-and-configure-ansible-automation-tool-for-it-management/2821
- make sure you have SSH connection between both machines by using ssh user@ipaddress --> https://gist.github.com/wacko/5577187
- create playbook containing a single play what will contain ansible install instructions 
- test my solution - green and yellow would be positive

!!! Text execution log file is included in the repository.
