
```
VAGRANT_VAGRANTFILE=Vagrantfile vagrant up

vagrant ssh-config

ansible --private-key=/Users/anirvan/vagrant-dev-env/.vagrant/machines/default/virtualbox/private_key -i inventories/development/vagrant/hosts -u vagrant -m ping all

ssh -i /Users/anirvan/vagrant-dev-env/.vagrant/machines/default/virtualbox/private_key vagrant@127.0.0.1 -p 2222

ansible-playbook -i inventories/development/vagrant/hosts playbooks/motd.yml
```
