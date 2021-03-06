TouchTog – Touchpad Toggle
================

## Contents

-   [Dependencies](#dependencies)
-   [Installation](#installation)
    -   [Universal](#universal)
    -   [Gentoo](#gentoo)
-   [Uninstallation](#uninstallation)
    -   [Universal](#universal-1)
    -   [Gentoo](#gentoo-1)

TouchTog is a simple program to toggle the touchpad.

## Dependencies

1.  xinput

## Installation

### Universal

``` sh
`# user` git clone https://github.com/amarakon/touchtog
`# user` cd touchtog
`# root` make install
```

### Gentoo

``` sh
`# root` eselect repository add amarlay git https://github.com/amarakon/amarlay
`# root` emerge --sync amarlay
`# root` emerge x11-apps/touchtog
```

## Uninstallation

### Universal

``` sh
`# user` cd touchtog
`# root` make uninstall
```

### Gentoo

``` sh
`# root` emerge -c x11-apps/touchtog
# Remove my overlay (optional)
`# root` eselect-repository remove -f amarlay
`# root` emerge --sync
```
