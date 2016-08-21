# ansible-vagrant-bsd

Trial for BSD setup with Vagrant and Ansible. Vagrant provisions a BSD system and sets up Python on it. Then later Ansible can run a ping against the system successfully.

## Getting Started
- Run `init.sh`
- Run `ansible -vvvvm ping all`

## Tuning
- Connect to box `ssh -v -i ~/Desktop/ansible-vagrant-bsd/.vagrant/machines/default/virtualbox/private_key -p 2222 vagrant@127.0.0.1`
- Delete box `vagrant destroy`