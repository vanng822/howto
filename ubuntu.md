##Register init script for startup at reboot in Ubuntu
```shell
cd /etc/init.d/
sudo update-rc.d {INIT.D_SCRIPT} defaults
sudo update-rc.d {SERVICE} disable
```
