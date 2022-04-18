# root
Utilities for Linux OS


## Set Keyboard layout

    # Set layout to Spanish
    sudo setxkbmap es
    
    # Set laout to English
    sudo setxkbmap us 


## stty 
    Ctrl+Z
    stty raw -echo; fg
    export TERM=xterm
    stty rows 51 cols 237

## find modes
    find / --perm -04000 -type f 2>/dev/null
    find /usr/ -type f -newermt '2022-01-01' -ls
