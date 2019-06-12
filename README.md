# ansible-plays-workspace

Ansible plays for bootstrapping my personal workspace on Ubuntu.

This playbook has been broken up into four individual role groups:

#### Common

* Install curl (cli http tool).
* Install gedit (gui text editor).
* Install gyazo screen capture.
* Install zsh shell.
* Install bash/zsh completion.
* Install elinks.
* Install i3 environment (with i3blocks).
* Install tmux.
* Install nitrogen.
* Install jq.

#### Development

* Install cmake.
* Install gcc7.
* Install watchman.
* Install pip2/pip3.
* Install Python 3.6 & 3.7.
* Install python development tools.
* Install pylint.
* Install pep8 core.
* Install httpie (cli http tool).
* Install aws-cli.
* Install docker.
* Install docker-compose.
* Install node.js 10 stable (using n tool).
* Install coffeescript.
* Install webpack.
* Install firebase tools.
* Install ruby.
* Install ruby dev tools.
* Install rails.
* Install travis-cli.
* Install mycli (interactive mysql cli).
* Install pgcli (interactive postgres cli).
* Install Go lang (stable).
* Install Dart 2.
* Install php7.
* Install composer (w/ laravel).
* Install datagrip.
* Install insomnia rest tool.
* Install vscode.
* Install vim and gvim.

#### Aesthetics

* Install Oranchelo icon theme.
* Install numix gtk theme.

#### Social

* Install slack desktop client.
* Install teamviewer.

## Variables

Playbook inventory variables can be found in `group_vars/all.yml`.

    git_ssh_key_user: Label of ssh key generated for git.

## Use

```sh
git clone https://github.com/neetjn/ansible-plays-elementary.git

cd ansible-plays-elementary

ansible-playbook playbook.yml
```

---

Copyright (c) 2019 John Nolette Licensed under the MIT license.
