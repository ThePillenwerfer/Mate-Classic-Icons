# Classic Icons for the Mate Desktop
  

This version downloaded from https://github.com/B00merang-Artwork/Windows-XP in June 2019, expanded and modified so that different document and image types show with different icons.

It has only been fully tested on Debian Stretch, Buster and Bookworm running the Mate desktop and briefly xfce and a Raspberry Pi running whatever its default DE is.  I haven't deliberately removed functionality for other desktops but may have done so by accident.

*Screenshots*

![screenshot_2018-06-19_15-02-42](https://github.com/ThePillenwerfer/Windows-XP/blob/master/Misc/Screenshot%20at%202019-06-16%2015-13-04.png)

![start](https://github.com/ThePillenwerfer/Windows-XP/blob/master/Misc/menu.png)



# INSTALLATION

For Debian-based distros click Releases and then **`mate-classic-icons_260213.deb`**.  If you have the `gdebi` package already installed double-clicking the downloaded .deb will install it.  Otherwise open a terminal and run:—

```
sudo apt install path-to/mate-classic-icons_260213_all.deb
```
so if it's in your Downloads directory you'd actually type:—
  
```
sudo apt install ~/Downloads/mate-classic-icons_260213_all.deb
```

For other distros click the green "Code" button then Download ZIP.  When this has downloaded open it and extract the `Mate-Classic-Icons-master` directory to `~/.icons`; you may have to press Ctrl-h to make it show in your file manager.

Now open the Mate Control Centre and click Appearance and choose the TraditionalOK theme.  Then click Customise followed by the Window Border tab and choose WinMe.  Now click the Icons tab and choose Mate-Classic.

Most icons will change immediately but a few, such as those in the Notification Area, only will after a reboot.

On older versions of Mate the Start button has to be changed manually by right clicking it then choosing Preferences.  Delete the contents of the 'Button text' box then click on the box next to the words 'Button icon:'.  Now navigate to `/usr/share/icons/mate-classic/Misc` or `~/.icons/Mate-Classic-Icons-master/Misc` and choose `Start.png` — again you may have to press Ctrl-h to make it show.

Sadly this has now been changed and the icon will change automatically but the text next to it will stay the same.  If you want it to say "Start" instead of "Menu" right click it and then choose Preferences and change it in the 'Button text' box.  It still won't look as good as it used to though.


# SUPPORT

There isn't any.  I did this for my own use but am happy to share it with anybody else who wants it.  However I don't really know what I am doing and am not going to even attempt to test it on multiple combinations of distros and desktops.

