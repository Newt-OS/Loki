# Loki Desktop Environment

These files are the configuration files for the Loki desktop environment.  More information about Loki at http://newtoslinux.weebly.com/loki.html

Software Components of Loki Desktop:
  - Plank (https://github.com/ricotz/plank)
  - Vala Panel (https://github.com/rilian-la-te/vala-panel)
  - Vala Panel Appmenu (https://github.com/rilian-la-te/vala-panel-appmenu)
  - Openbox (http://openbox.org/wiki/Main_Page)
  - LXDE Session, PCManFM (http://lxde.org/)
  - LightDM (https://freedesktop.org/wiki/Software/LightDM/)
  - LightDM GTK Greeter (https://launchpad.net/lightdm-gtk-greeter)
  - Synapse (https://launchpad.net/synapse-project)

Artistic Components
  - Arc Theme (https://github.com/horst3180/arc-theme)
  - Moka Icons (https://github.com/moka-project/moka-icon-theme)
  - Aller Font (https://www.fontsquirrel.com/fonts/aller)

The files in this repository rely on the above software components, and are simply just configurations to bring the components together.


This is a listing of where the files in this repository should be installed, and what the purpose is.

LeapFinal.png: /usr/share/wallpapers/       (default wallpaper)

autostart: /etc/xdg/lxsession/LXDE/         (autostart programs for LXsession)

config: /etc/xdg/vala-panel/default/        (set logout command for vala-panel)

displaymanager: /etc/sysconfig/             (set display manager)

desktop.conf: /etc/xdg/lxsession/LXDE/      (set gtk, icon, cursor themes)

lightdm-gtk-greeter.conf: /etc/lightdm/     (configure lightdm greeter)

panel: /etc/xdg/vala-panel/default/panels/  (panel layout and appearance)

pcmanfm.conf: /etc/xdg/pcmanfm/LXDE/        (set wallpaper, desktop settings)

rc.xml: /etc/xdg/openbox/LXDE/              (configure openbox)

skippy-xd.desktop: /usr/share/applications/ (set up skippy-xd program)

synapse.desktop: /usr/share/applications/   (set up synapse program)
