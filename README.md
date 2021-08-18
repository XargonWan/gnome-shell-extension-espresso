# Espresso
### An extension that enables controlling conditions to prevent the usual auto suspend and screensaver functions from taking effect.
Espresso is a fork of the Caffeine extension (https://github.com/eonpatapon/gnome-shell-extension-caffeine and provides essentially the same functionality. However Espresso only supports Gnome shell 40 whereas Caffeine also supports many prior Gnome shell versions as far back as 3.4

<b>Filled cup</b> = auto suspend and screensaver off. <b>Empty cup</b> = normal auto suspend and screensaver. 
![Screenshot](https://github.com/coadmunkee/gnome-shell-extension-espresso/raw/master/screenshot.png)

There are several Espresso options that can be configured ... 
![Preferences](https://github.com/coadmunkee/gnome-shell-extension-espresso/raw/master/screenshot-prefs.png)

## Installation from gnome.extension.org
[<img src="https://github.com/coadmunkee/gnome-shell-extension-espresso/raw/master/ego.png" height="100">](https://extensions.gnome.org/extension/4135/espresso)


For additional installation instructions and more information visit [https://github.com/coadmunkee/gnome-shell-extension-espresso/](https://github.com/coadmunkee/gnome-shell-extension-espresso/).


## Installation from git
    git clone git://github.com/coadmunkee/gnome-shell-extension-espresso.git
    cd gnome-shell-extension-espresso
    ./update-locale.sh
    glib-compile-schemas --strict --targetdir=espresso@coadmunkee.github.com/schemas/ espresso@coadmunkee.github.com/schemas
    cp -r espresso@coadmunkee.github.com ~/.local/share/gnome-shell/extensions

Restart the shell and then enable the extension.

## Report bugs on this site
[https://github.com/coadmunkee/gnome-shell-extension-espresso/issues](https://github.com/coadmunkee/gnome-shell-extension-espresso/issues)
