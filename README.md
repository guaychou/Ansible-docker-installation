# Ansible-docker-installation
This is ansible playbook for docker


## Installation
Clone this repo First

```sh
$ git clone https://github.com/guaychou/Ansible-docker-installation.git
```

Change to directory...

```sh
$ cd Ansible-docker-installation
```

### How to Run

Change <yourDistro> to specific Linux Distribution, for now only 2 available : Ubuntu, and manjaro

```sh
$ sudo ansible-playbook master.yml --extra-vars "my_distro=<yourDistro> username=`echo $USER`"
```

Example

```sh
$ sudo ansible-playbook master.yml --extra-vars "my_distro=ubuntu username=`echo $USER`"
```