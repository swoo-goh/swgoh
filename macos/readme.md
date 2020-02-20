# :high_brightness: Mac에 Linux 설치
* iMac mid 2011이 Macos Mojave 부터 지원하지 않아 Linux Server로 이용하자 함.
* iMac을 선택한 이유는 4코어 8쓰레드, 12G RAM (4EA), SSD, HDD를 장착했음에도, 모니터 ON시 55W, OFF시 35W의 전략사용량이 나오기 때문임.

### References
* https://www.howtogeek.com/187410/how-to-install-and-dual-boot-linux-on-a-mac/

# :high_brightness: Centos Fan Control on Mac

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
