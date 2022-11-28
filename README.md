# Notes
Nginx intallation script is under the scripts directory, and SSH keys is generated through terraform and can be acquired using terraform output command.   

 - To get the public IP use command:  " terraform output public_ip_address "
 - To get the private key for admin user: " terraform output tls_private_key "
 - User name: adminuser
