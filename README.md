# cachyos-umbriel-noctalia

[**Umbriel**](https://github.com/noctalia-dev/umbriel) is a Wayland compositor with *scrolling*, *dwindle*, *master* and *stacking* layouts, independent workspaces per monitor, and configurable visual effects.

[**Noctalia**](https://github.com/noctalia-dev/noctalia)  is a native Wayland desktop shell for people who want a polished, configurable Linux desktop without stitching together a separate bar, launcher, notification daemon, lock screen, wallpaper tool, and settings UI.

This repository loosely copies [cachyos-hypr-noctalia](https://github.com/CachyOS/cachyos-hypr-noctalia), with similar intentions.

Dependensies:

```Sh
adw-gtk-theme kitty xdg-desktop-portal xdg-desktop-portal-umbriel
```

## Post-install

### `Umbriel`

- in `~/.config/umbriel/config/outputs.toml` setup your monitor/s accordingly, follow example;

- in `~/.config/umbriel/config/environment.toml` setup your enviroments;

- in `~/.config/umbriel/config/inputs.toml` setup your input devices, such as keyboard, mouse, touchpad, touchscreen, tablet;

Rest are defaults.

### `uwsm`

In case you decided to use `uwsm` in `~/.config/uwsm` there is environment file, you could add your environments there and skip such step in `umbriel` setup.
