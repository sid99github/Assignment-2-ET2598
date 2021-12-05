# Assignment-2-ET2598
Automation with ansible
Managing virtual machines through secure shell remote logins, through ansible.
I have installed Ansible, Nginx, php and php-fpm.
Three Nginx servers running on three different platforms. We have HAproxy to load balance between these three servers.
I have an SSH config file that allows my host to use the Bastion host as a jump host, using an SSH key. The Bastion host has SSH access to all of the site-local hosts. 
