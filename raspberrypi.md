# Howto for Raspberry Pi

## HDMI power on/off
```bash
> # Off
> /usr/bin/tvservice -o
> # On
> /usr/bin/tvservice -p
```

## USB readonly file system problem
```bash
># This seems work
> sudo fsck.hfsplus /dev/sdXY
```
