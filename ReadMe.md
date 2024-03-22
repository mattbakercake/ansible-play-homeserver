# Ansible play to provision Home Server

## Notes
* update inventory file to point to correct host for installation
* run the play `ansible-playbook run.yaml --ask-become`

## extra info
play pulls down roles stored on github to local ansible host before execting them on the target machine
along with any other roles included in play

* docker
* portainer
* cockpit _[linux server web interface]_
* samba
* mergerfs _[storage pool jbod]_
* logitech media server
* homarr _[server resource webpage]_
* caddy _[reverse proxy/webserver]_