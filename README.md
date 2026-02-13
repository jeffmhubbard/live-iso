# live-iso
PENGUIN Live Desktop and Installer

## Update pacman.conf

    ...
    [penguin]
    Server = https://repo.penguin.fyi/$repo/$arch
    ...


## Create ISO

    cd live-iso
    sudo mkarchiso -rv penguin

