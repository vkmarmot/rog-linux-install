# rog-linux-install

1. Install as it says on asus-linux.org (i prefer not to install asusctl - it uses 2W of battery)
2. Set powertoys autotunes on start
```sh
crontab -e
```
```
@reboot /bin/sleep 6; /usr/sbin/powertop --auto-tune
```
