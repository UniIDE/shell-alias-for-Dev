# Bash Alias with Multiple Lines
sch:
- https://www.google.com/search?q=bash+alias+multiple+lines
- https://www.google.com/search?q=bash+alias+multiple+commands

## Discuss
https://askubuntu.com/questions/979327/create-a-bash-alias-for-several-commands-some-requiring-sudo

# Solution: use functions
https://stackoverflow.com/questions/756756/multiple-commands-in-an-alias-for-bash

>Try:
>```
>alias lock='gnome-screensaver; gnome-screensaver-command --lock'
>```
>or
>```
>lock() {
>    gnome-screensaver
>    gnome-screensaver-command --lock
>}
>```
