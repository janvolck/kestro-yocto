# Kestro Yocto

Repo manifests to setup yocto environment for kestro builds.

## Install repo

    mkdir -p $HOME/bin
    sudo apt install curl python
    curl https://storage.googleapis.com/git-repo-downloads/repo > $HOME/bin/repo
    chmod a+x $HOME/bin/repo

## Sync repo

    repo init -u git@github.com:janvolck/kestro-yocto.git -b master -m devices/rpi/default.xml
    repo sync
