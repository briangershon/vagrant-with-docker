vagrant-with-docker
===================

A `Vagrantfile` tailored for creating and running Docker containers.

Features
--------

* Installs latest Docker and Docker Compose

* SSH agent forwarding

* Ubuntu 14.04 LTS

Getting Started
---------------

1. For ssh forwarding, make sure your keys are added on your host system by running `ssh-add`

2. `vagrant up` to build and start the VM, and install Docker

3. `vagrant ssh` to connect to your new VM

4. On the VM, the `/vagrant` folder automatically syncs with your host filesystem so you can easily edit Dockerfiles, etc on your host system and use those in Vagrant.
