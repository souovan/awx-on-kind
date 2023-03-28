Ansible playbook to install AWX on KIND cluster

current working on:
* Ubuntu
* Debian
* Fedora
* CentOS

future: 
wsl-ubuntu

## pre-req
2 vcpus
4 gb ram

## Usage
* Install ansible
```sh
git clone https://github.com/souovan/awx-on-kind.git # Clone this repo
cd awx-on-kind # Enter the repo directory 
ansible-playbook awx_on_kind.yaml -K # Run the playbook awx_on_kind.yaml 
```


## How to install Ansible Distros

### Debian and Ubuntu
```sh
sudo apt update && sudo apt install -y ansible
```

### Fedora
```sh
sudo dnf install -y ansible
```

### Centos
```sh
sudo rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm && sudo yum -y install ansible
```

