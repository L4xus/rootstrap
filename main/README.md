```
# COPYrIGHT 2020 L4xus
# ROOTSTRAP INSTALL

# install flag
if  [[ $1 = "-install" ]]; then
    echo "please give a package to install..."
fi

# termux chess package by L4xus

if  [[ $1 = "-install" ][ $2 = "--chess" ]]; then
    echo "installing chess..."
    FILE=/data/data.com.termux/files/usr/.rstrap
    if test -f "$FILE"; then
        echo "$FILE exists meaning rootstrap is installed..."
        FILE2=/data/data.com.termux/files/rootstrap/.rstrap_direc
        if test -f "$FILE2"; then
            Rootstrap directories is installed proceeding...
            # start install script here:
            cd /data/data/com.termux/files/rootstrap/install-scripts/
            mkdir termux-chess
            cd termux-chess
            wget https://rstrap.github.io/repo/install-scripts/official/termux-chess/install.sh
            bash install.sh
        else
            install for legacy devices at https://github.com/rstrap/rootstrap/
    else
        echo install rootstrap from https://github.com/rstrap/rootstrap/
fi
```
