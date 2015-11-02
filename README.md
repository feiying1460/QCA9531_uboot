# QCA9531_uboot
A.Compile:
1. cd uboot/build。
2. make DEV_NAME=wr841nv9_en toolchain_prep。
3. make DEV_NAME=wr841nv9_en fs_prep。
4. make DEV_NAME=wr841nv9_en COMPRESSED_UBOOT=1 FLASH_SIZE=8 uboot。

B.Web upgrade:
1. set Computer ip : 192.168.1.100
2. press RESET button then power on
3. wait 5 seconds and http://192.168.1.1

