ansible-dev-machine
===================

```
sudo add-apt-repository ppa:rquillo/ansible
sudo apt-get update
sudo apt-get install ansible git-core

mkdir -p ~/Projects/vespakoen/code/
git clone git@github.com:vespakoen/ansible-dev-machine.git ~/Projects/vespakoen/code/

cd ~/Projects/vespakoen/code

sudo cp ansible-hosts /etc/ansible/hosts

sudo ansible-playbook --connection=local locales.yml
sudo ansible-playbook --connection=local virtualbox.yml
sudo ansible-playbook --connection=local vagrant.yml
sudo ansible-playbook --connection=local sublime-text.yml
sudo ansible-playbook --connection=local xmonad.yml
```
