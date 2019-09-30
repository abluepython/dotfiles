# dotfiles

## Requirements

* python3.6
* pip3 
* plug
* pynvim
* jedi

## Install

Install vim-plug using this command:
```bash
    curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
Install pynvim and jedi using pip3
```bash
    pip3 install --user pynvim
    pip3 install --user jedi
```


### How to use vim-plug

You can execute following command in Nvim comand mode:

* Install plugins：:PlugInstall
* Update plugins：:PlugUpdate
* Remove plugins：:PlugClean (First, comment the plugin install command in init.vim. Open Nvim and use :PlugClean to uninstall plugins)
* Check the plugin status：:PlugStatus
* Upgrade vim-plug itself：:PlugUpgrade


### Comment plugin

To comment out a single line, use <leader>cc (leader is a prefix key in Nvim, the default leader key is ["\"]); to un-comment a line, use <leader>cu. 
To comment or uncomment several lines, add a repeating number to corresponding command, just like what you do in plain Vim. For more usages, 
check [nerdcommenter’s documentaion](https://github.com/scrooloose/nerdcommenter)
