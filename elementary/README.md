# [Elementary OS](https://elementary.io)

## Install apt appended commends
- Include add-apt-repository
``` Shell
sudo apt install software-properties-common
```

## Tweak
- [Official](https://github.com/elementary-tweaks/elementary-tweaks)
``` Shell
sudo add-apt-repository ppa:philip.scott/elementary-tweaks
sudo apt install elementary-tweaks
```

## Wingpanel System Monitor
- [Official](https://github.com/PlugaruT/wingpanel-indicator-sys-monitor)
``` Shell
# You need to git clone
meson build --prefix=/usr
cd build
ninja && sudo ninja install
```

## Recommend On Appcenter
### DB Manager
#### Sequeler
- [AppCenter](https://appcenter.elementary.io/com.github.alecaddd.sequeler/)
- [Official Repository](https://github.com/Alecaddd/sequeler)

### Package Installer
#### Eddy (Debian)
- [AppCenter](https://appcenter.elementary.io/com.github.donadigo.eddy/)
- [Official Repository](https://github.com/donadigo/eddy)

#### Snaptastic (Snap)
- [AppCenter](https://appcenter.elementary.io/com.github.bartzaalberg.snaptastic/)
- [Official Repository](https://github.com/bartzaalberg/snaptastic)

### Disk Image
#### Image Bunner
- [AppCenter](https://appcenter.elementary.io/com.github.artemanufrij.imageburner/)
- [Official Repository](https://artemanufrij.github.io)
