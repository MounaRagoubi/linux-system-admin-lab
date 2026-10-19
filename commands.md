# Linux commands

## System Information

``bash``

uname -a

hostname

whoami

## Users and Groups
sudo adduser testuser

sudo groupadd developers

sudo usermod -aG developers testuser


## File Persmissions

ls -l

chmod 755 file.sh

chown user:group file.txt


## Services 

systemctl status ssh

sudo systemctl restart ssh


## Logs

journalctl

journalctl -u ssh


## Networking 

ip a

ip route

ping 8.8.8.8
