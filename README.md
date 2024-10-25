dottmux
=======

mjt's .tmux stuff

Installation
------------

    git clone git://github.com/mjtorn/dottmux.git .tmux/ --recurse-submodules

    ln -s .tmux/tmux.conf .tmux.conf

You can create a file `~/.tmux/local.tmux.conf` with host-specific things.

Resurrection
------------

Saving is the default `C-a C-s` for all sessions in the socket.

Maybe this works automatically if there's a ``main`` default
session name, but as I usually name all of them, a new session
with any saved name should likely exist and then `C-a C-r`
should restore all of them.

Battery status
--------------

If you run on a laptop, install upower and `echo -n /org/freedesktop/UPower/devices/battery_BAT0 > ${HOME}/.tmux/battery`.

