# Desktop Configuration Manager

### Usage

Use server config
* $ bash setup.sh -s 

Use Desktop config
* $ bash setup.sh -d

### Behaviours
* Delete existing .bashrc, .vimrc or .tmux.conf in /home/$USER
* Create symbolic links from the github repo to /home/$USER
* Clone Vundle to .vim from github

### Note
This script only supports Vundle
