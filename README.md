## brunch-things (for Project: [brunch](https://github.com/sebanc/brunch) courtesy of developer: [sebanc](https://github.com/sebanc))

#### Files for backing up and restoring 'brioche' containers  

##### (Other things too hopefully ...)

-------------
```
## brio-br - A script to list, backup and restore brioche containers

USAGE:'brio-br -b / brio-b / brio-backup'
        Backs up brioche containers found under '~/brioche/'
        to '/home/chronos/user/Downloads' (default: ~/Downloads).
        The script will prompt for each container before proceeding.

                                -or-

USAGE:'brio-br -r / brio-r / brio-restore'
        Restores brioche container backups found under '/home/chronos/user/Downloads'
        (default: ~/Downloads) to the named container under '~/brioche/'.
        The script will prompt for each container before proceeding.
        and append the last modified date & time to any existing container folders found.

NOTE: Please use 'install.brio-br' to install and link the above scripts automagically.
    ( URL:https://raw.githubusercontent.com/DennisLfromGA/brunch-things/main/install.brio-br ) 

Specify backup (-b) or restore (-r) as command-line optons.
Optionally displays help/options, usage, script version, & version history then exits

Options:
        -b    List & backup brioche containers
        -r    List & restore brioche containers
        -h    Displays help message for options (this blurb)
        -u    Displays usage for backup and restore and exits
        -v    Displays the current version of 'brio-br' and exits
        -V    Displays version number plus version history & exits
```
-----------------
```
'install.brio-br': A script to install 'brio-br' and associated links to '/usr/local/bin' as root (default)

IMPORTANT: To initially download, install & run this script enter:

        cd /tmp &&\
        curl -LO https://raw.githubusercontent.com/DennisLfromGA/brunch-things/main/install.brio-br &&\
        sudo install -Dt /usr/local/bin -m 755 install.brio-br && /usr/local/bin/install.brio-br

Once installed the script will autoupdate if needed when it's run.

Will link: 'brio-b' & 'brio-backup'  to 'brio-br' which forces those scripts to run the 'backup'  option.
Will link: 'brio-r' & 'brio-restore' to 'brio-br' which forces those scripts to run the 'restore' option.

Usage: 'install.brio-br' [-h|-i|-l|-u|-f|-c|-v|-V] (see Help/Options)

Note: To replace the install PATH (default: /usr/local/bin) prepend 'install.brio-br' with BIN=your/path
      To replace the file permissions (default 755) prepend 'install.brio-br' with PERM=nnn
      To execute 'install.brio-br' as user 'chronos' instead of 'root' (default) prepend 'install.brio-br' with SUDO=' '

      (I.E.) BIN=~/bin PERM=775 SUDO=' ' install.brio-br

Options:
        -h    Displays help message for options (this blurb)
        -i    Displays instructions for initial download, install and running this script
        -l    Lists installed files & links under /usr/local/bin
        -u    Displays usage for backup and restore
        -f    Force update of brio-br & install.brio-br
        -c    Check if installed versions of 'install.brio-br' & 'brio-br' are up-to-date
        -v    Displays the current version of 'install.brio-br'
        -V    Displays version number plus version history```
---------------
