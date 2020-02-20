# Centos Fan Control on Mac

lm_sensors, pwmconfig, fancontrol을 이용하는 방법은 Mac에서 사용할 없어 직접 Shell로 제어하고 함

### Fan Control Shell Script
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

### Crontab 등록
```shell
# crontab -e
```
```shell
*/1 * * * * /bin/bash /root/fancontrol.sh
```
