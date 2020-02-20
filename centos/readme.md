# :high_brightness: hdparm HDD spindown
### 설치
```shell
# yum install hdparm
```
```shell
# lsblk --output NAME,FSTYPE,LABEL,UUID,MODE

NAME   FSTYPE  LABEL       UUID                                 MODE
sda                                                             brw-rw----
├─sda1 vfat    EFI         67E3-17ED                            brw-rw----
├─sda2                                                          brw-rw----
└─sda3 hfsplus Recovery HD 59a24947-d9eb-30e0-acf5-4f7ea9d66afc brw-rw----
sdb                                                             brw-rw----
├─sdb1 vfat    EFI         67E3-17ED                            brw-rw----
├─sdb2                                                          brw-rw----
├─sdb3 vfat                B1AC-7175                            brw-rw----
├─sdb4 ext4                1abaac2e-1149-47c2-a206-ce62c87ed01b brw-rw----
├─sdb5 ext4                0e3e608b-6b98-42d5-b8d2-74262de9d181 brw-rw----
└─sdb6 swap                cd1072df-91eb-4031-af9d-f0ea72335016 brw-rw----
```
```shell
# vi /etc/hdparm.conf
```
입력값의 5배에 해당하는 초후에 스핀다운이 된다. (60이면 5분)
```shell
/dev/sdb {
    spindown_time = 60
}
```
