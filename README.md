ansible-dev-machine
===================

```
sudo add-apt-repository ppa:rquillo/ansible
sudo apt-get update
sudo apt-get install ansible git-core

cd ~
git clone git@github.com:vespakoen/ansible-dev-machine.git
cd ansible-dev-machine
sudo cp ansible-hosts /etc/ansible/hosts

sudo ansible-playbook --connection=local locales.yml
sudo ansible-playbook --connection=local virtualbox.yml
sudo ansible-playbook --connection=local vagrant.yml
sudo ansible-playbook --connection=local sublime-text.yml
sudo ansible-playbook --connection=local xmonad.yml
sudo ansible-playbook --connection=local xmodmap.yml
sudo ansible-playbook --connection=local zsh.yml
sudo ansible-playbook --connection=local spf13vim.yml
sudo ansible-playbook --connection=local theme.yml
```
