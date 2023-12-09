
# Workflow
We are goind to build 4 servers using Vagrant, after creating the servers we are going to use Ansible to run a Playbook that will automate the configuration of the servers
After the servers are configured we will containerize a simple web application and finally we will convert the servers to docker swarm and bring the application to swarm
The password for all vm's is vagrant

# Requirements
In this project I'm going to install all the requirements 

- Vagrant
- Oracle VirtualBox
- Docker
- Docker Compose
- Ansible

# Install Vagrant
https://www.vagrantup.com/docs/installation



# Install Oracle Virtualbox

https://www.vagrantup.com/docs/providers/virtualbox


# Install Visual Studio Code

https://code.visualstudio.com/downloadvi



# Lab
```
vagrant up
vagrant ssh control
```

### Copy over hosts file

```
sudo cp /vagrant/hosts /etc/hosts
```

![Vagrant Ansible Docker]9https://youtu.be/35XgxR_TSc8)
