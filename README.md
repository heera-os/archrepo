# Archlinux Repository for Heera OS

If you prefer more stable releases (versioned), see https://github.com/heera-os/archrepo-stable

### Usage

Add following lines to your /etc/pacman.conf.

```
[heera-git]
SigLevel = Optional
Server = https://heera-os.github.io/archrepo/$arch/
```

> Then to use Heera DE, install all packages of group `heera-git`, and run `startx /usr/bin/heera-session` (ie. if not using a window manager, like [gdm](https://wiki.archlinux.org/title/GDM))

These packages are built by Github Actions, and from the latest -git sources, hence may provide additional features as the heera os repositories are updated.

* All of these packages belong to the `heera-git` group

Checkout the Heera OS repositories at https://github.com/heera-os
