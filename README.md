ansible-dev-machine
===================

```
sudo add-apt-repository ppa:rquillo/ansible
sudo apt-get update
sudo apt-get install ansible

mkdir -p ~/Projects/vespakoen/code/
git clone git@github.com:vespakoen/ansible-dev-machine.git ~/Projects/vespakoen/code/

cd ~Projects/vespakoen/code

sudo ansible-playbook --connection=local locales.yml
```
