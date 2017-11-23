
# GtkEmacs-debug-ito

This is my Emacs-like keybinding settings for Gtk+ 3.

This is based on the "Emacs" theme file distributed in a Ubuntu package libgtk-3-common (3.18.9-1ubuntu3.3). See `original` directory for original authors and license information.

# How to use

1. Clone this repository.

        $ git clone https://github.com/debug-ito/GtkEmacs-debug-ito.git

2. Add link to your themes directory

        $ mkdir -p ~/.themes
        $ ln -s GtkEmacs-debug-ito ~/.themes/

3. Set the theme.

        $ gsettings set org.gnome.desktop.interface gtk-key-theme GtkEmacs-debug-ito
 
   In XFCE:

        $ xfconf-query -c xsettings -p /Gtk/KeyThemeName -s GtkEmacs-debug-ito

4. (Maybe you have to write `~/.config/gtk-3.0/settings.ini` file)

        [Settings]
        gtk-key-theme-name = GtkEmacs-debug-ito

See also:

- [GTK+ - ArchWiki](https://wiki.archlinux.org/index.php/GTK%2B#Emacs_keybindings)


# Author

Toshio Ito <debug.ito@gmail.com>
