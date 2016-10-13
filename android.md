## Emulator and localhost
Assume server at port 8090 on laptop and you have device emulator-5554

```bash
> adb -s emulator-5554 reverse tcp:8090 tcp:8090
```
