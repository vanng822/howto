# Terminal locale/encoding
Problem displaying unicode characters such as Vietnamese in terminal. Check locale settings and charmap

## Check settings
```bash
> locale
> locale charmap
> locale -a
> locale -m
```

## Setting up for console
```bash
> dpkg-reconfigure console-setup
```
Choose UFT-8 and combined Latin and Vietnamse
