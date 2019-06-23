Symlink python files from terminator project to the ones here. For newer
versions may need to rebase changes, copying original scripts again.

    cd /usr/share/terminator/terminatorlib
    sudo mv config.pyc config.pyc.bak
    sudo mv prefseditor.pyc prefseditor.pyc.bak
    sudo mv terminal.pyc terminal.pyc.bak 
    sudo mv config config.bak
    sudo mv prefseditor prefseditor.bak
    sudo mv terminal terminal.bak 
    sudo ln -s /home/me/Code/terminator-mods/terminal.py terminal.py
    sudo ln -s /home/me/Code/terminator-mods/prefseditor.py prefseditor.py
    sudo ln -s /home/me/Code/terminator-mods/config.py config.py
