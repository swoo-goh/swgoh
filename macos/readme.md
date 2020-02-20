# Centos Fan Control on Macos (Macbook, iMac ...)

```shell
# vi /root/fancontrol.sh
```
```shell
#!/bin/bash

FAN_RPM=1000

if [ 0 -eq `cat /sys/devices/platform/applesmc.768/fan1_manual` ]; then
    echo 1 > /sys/devices/platform/applesmc.768/fan1_manual
fi

if [ ${FAN_RPM} -ne `cat /sys/devices/platform/applesmc.768/fan1_max` ]; then
    echo ${FAN_RPM} > /sys/devices/platform/applesmc.768/fan1_max > /sys/devices/platform/applesmc.768/fan1_min
fi
```

```shell
# crontab -e
```
```shell
*/1 * * * * /bin/bash /root/fancontrol.sh
```
