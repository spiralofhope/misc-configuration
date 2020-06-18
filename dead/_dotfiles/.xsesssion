

# /usr/lib/X11/xdm/Xsession
# ~/.xsession


# Screen Saver
xscreensaver-command -exit
xscreensaver &

# For reasons I don't understand, this line is required, otherwise
# a kde-bloated session would start up.
exec openbox-session



:<<'}'   #  Old notes
{
#!/bin/sh

# s  = don't display groundplate
# no = Use non-qt configuration tool
# i  = iconic (don't display the thing)
# w  = withdrawn (place it in the slit)
# bbkeys keeps dying on me.  Sigh.
exec /usr/local/bin/bbkeys&
exec /usr/X11R6/bin/xscreensaver&
#-i -no -display :0.0&

# start a nice shell
exec $HOME/scripts/rxvt.sh&
# -exec <whatever>, such as:
# -exec zsh

# Start the window manager:
# Just in case it dies, restart it.  =)
# probably don't need this:
until /usr/local/bin/blackbox; do :; done
#/usr/X11R6/bin/fluxbox
}
