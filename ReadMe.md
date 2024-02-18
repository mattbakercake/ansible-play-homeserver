# Ansible play to provision Home Server

## Notes
* update inventory file to point to correct host for installation
* run the play `ansible-playbook run.yaml --ask-become`

## extra info
play pulls down roles stored on github to local ansible host before execting them on the target machine
along with any other roles included in play

* docker
* cockpit
* samba
* mergerfs
* logitech media server