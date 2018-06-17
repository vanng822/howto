# Write
```bash
time dd if=/dev/zero bs=2048k of=tstfile count=1024 2>&1 | awk '/sec/ {print $1 / $5 / 1048576, "MB/sec" }'
```

## Read
```bash
time dd if=tstfile bs=2048k of=/dev/null count=1024 2>&1 | awk '/sec/ {print $1 / $5 / 1048576, "MB/sec" }'
```
