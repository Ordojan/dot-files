# Installation:

    cd ~
    git clone git@github.com:Ordojan/dot-files.git

### Delete current bash files

    rm ~/.bashrc ~/.bash_aliases ~/.bash_profile

### Create symlinks:

    ln -s ~/dot-files/bashrc ~/.bashrc
    ln -s ~/dot-files/bash_aliases ~/.bash_aliases
    ln -s ~/dot-files/bash_profile ~/.bash_profile
  
### Setup git submodules:

    git submodule init
    
    git submodule update
  
### Update git submodules:

    git submodule foreach git pull origin master

### Follow the steps from the dot-vim repository

    https://github.com/Ordojan/dot-vim
