Al's Example Ansible Code I use to setup a LEMP Server from a ubunutu 
========================

Al Example Ansible Code i use to setup a Linux, Nginx, MySQL, PHP Stack from a Ubuntu Digital Ocean droplet template.

Add Users to Droplet
----------
* Install Phyton 2 on the Server
* This code resets the root password to a know passord
* Add new admin users to server, copys their public SSH keys to the server add to them sudo users group
* Disable root login and password login in SSHD and Restarts SSHD
