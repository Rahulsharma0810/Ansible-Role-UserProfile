# Ansible-Role-UserProfile
Role to tweak user profile using bashrc and vimrc.

#### Usage
- Role is User Based but needs sudo to install vim
- Define user in vars/main.yml ```profile_user: sweetuser```

#### SAFE-RM
- Implemented Safe-rm Trash folder
- Every rm -rf command move file to ```~/.local/share/Trash/files/```


#### Vim Tweaks
-  Autosave file before modity in ```~/.local/share/Trash/files/``` with prefix ```filename-date.VIM```

```
set number 	"Set Number
syntax enable   " enable syntax processing
set showcmd     " show command in bottom bar
set cursorline  " highlight current line
set wildmenu    " visual autocomplete for command menu
set showmatch   " highlight matching [{()}]
```

