# ColourMe-SSH
How to add colour to SSH! Stop those Black and White awful Commandlines! :)

Add this into the `.bash_profile` file! in the home directory of the User you are connecting or utilizing.

```
export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -GFh'
```
### From this:
![After](https://i.imgur.com/5oFcAJa.png)
### To this:
![After](https://i.imgur.com/fueETXV.png)
