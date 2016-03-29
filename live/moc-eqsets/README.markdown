Equalizer presets for Music on Console

  http://moc.daper.net/

Thanks to [hiben](http://moc.daper.net/comment/3973#comment-3973).
Though his link is broken, I found the presets [on archive.org](http://wayback.archive.org/web/20120621042346/http://www.informatik.uni-bremen.de/~hiben/moc/eqsets.tar.gz).  
Thanking them goes without saying.  Archive.org is incredible.

These files go in `~/.moc/eqsets/`

Once there, they are used by moc with:

```
E              Toggles the equalizer
e              Reload EQ-presets
K              Select previous equalizer-preset
k              Select next equalizer-preset
```

To make your equalizer selection permanent, edit `~/.moc/config` with:

```
# Save equalizer state?
# If enabled, a file 'equalizer' will be created in '~/.moc/' storing the
# equalizer settings when the server is shut down.
# Note that there is a "hidden" 'Mixin' setting in that file.
# Mixin (0.0-1.0) is used to determine how much of the original signal is
# used after equalizing.  0 means to only use the equalized sound, while 1
# effectively disabled the mixer.  The default is 0.25.
#Equalizer_SaveState = yes
```

Note that the companion README_equalizer file is a copy from moc 
2.5.0-beta1, copied from `/usr/doc/moc-2.5.0-beta1/README_equalizer`
