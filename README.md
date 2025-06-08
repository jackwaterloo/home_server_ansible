# home_server_ansible
Automatically provisions my ubuntu server exactly how I want it. Focus is on initial setup of server and auto-setup pi-hole. Potentially will add more applications later.

## Setup on host machine

[This](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html#installing-ansible-on-ubuntu) is how you install ansible on Ubuntu.

```bash
sudo apt update

sudo apt install software-properties-common

sudo add-apt-repository --yes --update ppa:ansible ansible

sudo apt install ansible
```

### Managing Docker

docker ansible documentation [here](https://galaxy.ansible.com/ui/repo/published/community/docker/). Make sure to install the correct dependencies on host (ansible galaxy docker) and install correct requriements on client (python docker sdk and other dependencies)
