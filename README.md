# EmbeddedLinuxBBB ;

Links:
https://beagleboard.org/black
https://globallogic.udemy.com/course/embedded-linux-step-by-step-using-beaglebone/learn/lecture/7802556#overview
https://elinux.org/Beagleboard:BeagleBoneBlack

Board Overview
2) Embedded MMC (eMMC)
The board has 4GB of eMMC(embedded Multi Media Controller) memory chip, This is an on-board  memory chip that holds up to 4GB of data in BBB Rev C.

Accessing data from this memory is much faster than accessing through external micro sd card , and remember that the board boots from this memory by default. But you can always change, from where the boot should boot, more on this is covered later. 

3) SDRAM Memory: 512MB DDR3 

This is external Dynamic RAM memory, the board comes with SDRAM Memory: 512MB DDR3. This is on the board and connected to SOC. I will cover more on memory interfaces later in this course. They claim this memory as, faster and low power RAM memory. During booting the boot images will get loaded to this RAM from other memories and will execute from here, more on this later.

Practice Notes:
- dmesg           --> to debug the linux syslog messages
- sudo minicom -s --> to configure minicom first time
- what is SYSFS in linux?
- 
 
