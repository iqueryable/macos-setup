## Install Xcode 

```sh
xcode-select --install
xcodebuild -license accept
softwareupdate --install-rosetta
```

## Ansible

```
sudo python3 -m pip install --upgrade pip
sudo python3 -m pip install ansible
```

## Pre-requisites

- Set machine
- Github access token

## Install

```
ansible-playbook main.yaml --ask-become-pass
```

## Post install

- Set password on ssh key

## TODO

- more zshrc stuff
- iterm colors
- zsh theme
- zprofile
