# lxi-tools.snapcraft

This repository contains the snapcraft configuration used for creating the lxi-tools snap.

The official snap is available at https://snapcraft.io/lxi-tools

Visit https://snapcraft.io to see how to use snaps on your distribution.

Build:
```
snapcraft
```

Install:
```
snap install <snap file>
```

Run:
```
lxi-tools.lxi-gui
lxi-tools.lxi
```

Note: snap package supports accent colors. It works out of the box on GNOME desktop enviroment.
For non GNOME desktop enviroments snap can take default accent color which is orange in snap package.
Accent color can be changed with variable ADW_DEBUG_ACCENT_COLOR. 

```
    $ env ADW_DEBUG_ACCENT_COLOR=blue  lxi-tools.lxi-gui
```

Possible colors:
```
    blue, teal, green, yellow, orange, red, pink, purple, slate, brown
```
