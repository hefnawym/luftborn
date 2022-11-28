# Notes
In order to be able to apply the terraform plan, you need first to login to your azure account using azure cli from your terminal. 
Nginx intallation script is under the scripts directory, and SSH keys is generated through terraform and can be acquired using terraform output command.  

 - Requird Terraform version: 1.3.5
 - To get the public IP use command:  " terraform output public_ip_address "
 - To get the private key for admin user: " terraform output tls_private_key "
 - User name: adminuser
