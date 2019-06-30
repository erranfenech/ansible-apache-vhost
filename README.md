# ansible-apache-vhost
Create Virtual host configuration, prompt for domain name and document root location.

Example of how to execute:
ansible-playbook main.yml -t "create-vhost" -k -i "134.213.177.143," -c paramiko
