Source link:
---
https://wiki.archlinux.org/title/Cinnamon#Portable_keybindings

To export the keyboard shortcut keys:
```
dconf dump /org/cinnamon/desktop/keybindings/ > keybindings-backup.dconf
```

To import it on another device:
```
dconf load /org/cinnamon/desktop/keybindings/ < keybindings-backup.dconf
```

