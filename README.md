RomBOOT
Starting NoBrick-BS
Board Type... Intrepid 1.5
df reader init (0x0)...Spansion 256Mb
Boot device: SPI    chip id: 20C6:0E10:36BF:98CE:2CFF:7C71:3E3F:EF14
df reader init (0x0)...Spansion 256Mb
   chip id: 20C6:0E10:36BF:98CE:2CFF:7C71:3E3F:EF14
df reader init (0x1)...Spansion 256Mb
   chip id: 0CF6:8156:4FA1:439E:20DB:3F45:21C3:12CE
Loading part 2 of BS...
  using 0x0
Done

ChipID: 0x01AC

-E- No NandFlash detected !!!
bad i2c checksum: 0E00:00EA:0500:00EA
bad i2c checksum: 0500:00EA:0500:00EA
bad i2c checksum: 0500:00EA:2038:0000
bad i2c checksum: 0500:00EA:0500:00EA
bad i2c checksum: FEFF:FFEA:FEFF:FFEA
bad i2c checksum: FEFF:FFEA:FEFF:FFEA
bad i2c checksum: FEFF:FFEA:FEFF:FFEA
bad i2c checksum: FEFF:FFEA:0340:0000
i2c serial number: FEFF:FFEA:0340:0000
f1id UID match
f2id UID match

Board number: 0xA205
Board number: 
0x3
NAND to alternative
console=ttyS0,115200 root=/dev/ram0 rw mtdparts=atmel_nand:32768K(local0),32768K(local1),32768K(local2),32768K(local3),32768K(local4),-(data) imageDevs=spi0.0,spi0.1log_copy_kernel
Log: 0x00303B10
   [0x004C0000, 0x00500000): 0x00203824
Meta Data for Log: 0x00303B10
	memStart:      0x004C0000
	memStop:       0x00500000
	head:          0x004C0000
	tail:          0x004C3A00
	nextFreeSlot:  0x004C3B00
	nextSeqNum:    0x0000003C
	write size:    0x00000100
Log: 0x00303B34
   [0x01FC0000, 0x02000000): 0x00203824
Meta Data for Log: 0x00303B34
	memStart:      0x01FC0000
	memStop:       0x02000000
	head:          0x01FC0000
	tail:          0x01FC3A00
	nextFreeSlot:  0x01FC3B00
	nextSeqNum:    0x0000003C
	write size:    0x00000100
Log: 0x00303B58
   [0x004C0000, 0x00500000): 0x00203878
Meta Data for Log: 0x00303B58
	memStart:      0x004C0000
	memStop:       0x00500000
	head:          0x004C0000
	tail:          0x004C3A00
	nextFreeSlot:  0x004C3B00
	nextSeqNum:    0x0000003C
	write size:    0x00000100
Log: 0x00303B7C
   [0x01FC0000, 0x02000000): 0x00203878
Meta Data for Log: 0x00303B7C
	memStart:      0x01FC0000
	memStop:       0x02000000
	head:          0x01FC0000
	tail:          0x01FC3A00
	nextFreeSlot:  0x01FC3B00
	nextSeqNum:    0x0000003C
	write size:    0x00000100
Log: 0x00303BA0
   [0x00010000, 0x0001FFFF): 0x002038CC
Meta Data for Log: 0x00303BA0
	memStart:      0x00010000
	memStop:       0x0001FFFF
	head:          0x00010000
	tail:          0x00013A00
	nextFreeSlot:  0x00013B00
	nextSeqNum:    0x0000003C
	write size:    0x00000100
Post Scan State: 
	reqBootKern:      0x0001
	reqBootFDT:    0x0001
	reqBootInitrd:    0x0001
	reqBootFS:        0x0001
	bootSeqNum:       0x00000007
	Kernel Table - 
	tabVers:      0x00000001
	   [0x0] - 
		vers:       0x0001
		offset:     0x00040000
		len:        0x0017AF8C
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        A2A2:79B9:82D1:C3F2:52BF:E10E:E3DD:FD33
		attemptCnt: 0x00000041
		successCnt: 0x00000041
	   [0x1] - 
		vers:       0x0001
		offset:     0x00500000
		len:        0x0017AF8C
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        A2A2:79B9:82D1:C3F2:52BF:E10E:E3DD:FD33
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x2] - empty
	   [0x3] - empty
	   [0x4] - empty
	   [0x5] - empty
	   [0x6] - empty
	FDT Table - 
	tabVers:      0x00000003
	   [0x0] - empty
	   [0x1] - empty
	   [0x2] - empty
	   [0x3] - empty
	   [0x4] - empty
	   [0x5] - empty
	   [0x6] - empty
	Initrd Table - 
	tabVers:      0x00000002
	   [0x00] - 
		vers:       0x0001
		offset:     0x001C0000
		len:        0x002CB679
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        EBB4:3B81:3AAD:4609:61CA:0FD4:4333:CF90
		attemptCnt: 0x00000041
		successCnt: 0x00000041
	   [0x01] - 
		vers:       0x0001
		offset:     0x00680000
		len:        0x002CB679
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        EBB4:3B81:3AAD:4609:61CA:0FD4:4333:CF90
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x02] - empty
	   [0x03] - empty
	   [0x04] - empty
	   [0x05] - empty
	   [0x06] - empty
	FS Table - 
	tabVers:      0x00000006
	   [0x000] - 
		vers:       0x0001
		offset:     0x00000000
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x001] - 
		vers:       0x0001
		offset:     0x00000001
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x002] - 
		vers:       0x0001
		offset:     0x00000002
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x003] - 
		vers:       0x0001
		offset:     0x00000003
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x004] - 
		vers:       0x0001
		offset:     0x00000004
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x005] - 
		vers:       0x0001
		offset:     0x00000005
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x006] - empty
	   [0x007] - empty
	   [0x008] - empty
	   [0x009] - empty
	   [0x00A] - empty
	   [0x00B] - empty
	   [0x00C] - empty
	   [0x00D] - empty
Evaluating MD5 File Table 0x0/0x0: 
	version compat check: 
	minVers: 0xFFFE
	myVers: 0x0001
	maxVers: 0x0001
    Evaluating MD5 File Table 0x1/0x0: 
empty
	version compat check: 
	minVers: 0xFFFE
	myVers: 0x0000
	maxVers: 0x0001
        Evaluating MD5 File Table 0x2/0x0: 
	version compat check: 
	minVers: 0x0000
	myVers: 0x0001
	maxVers: 0x0001
Loading file[0x2/0x0] from 0x001C0000 len 0x002CB679 to 0x20800000
good
good
Loading file[0x0/0x0] from 0x00040000 len 0x0017AF8C to 0x20008000
good
Attempting boot:
	kernel 0x0
	initrd 0x0
	rootfs 0x0
Write to 0x004C3B00 successful
Write to 0x01FC3B00 successful
Write to 0x004C3B00 successful
Write to 0x01FC3B00 successful
Write to 0x00013B00 successful
Uncompressing Linux...
.............................................................................................. done, booting the kernel.
Linux version 2.6.30.2 (falconode@falconode-HP-ProBook-640-G3) (gcc version 4.7.3 (Buildroot 2012.05-g08977ee) ) #1 Mon Jan 28 17:04:34 MST 2019
CPU: ARM926EJ-S [41069265] revision 5 (ARMv5TEJ), cr=00053177
CPU: VIVT data cache, VIVT instruction cache
Machine: PolySat Avionics Board, version 1
Memory policy: ECC disabled, Data cache writeback
Ignoring RAM at 00200000-00203fff (vmalloc region overlap).
Ignoring RAM at 00300000-00303fff (vmalloc region overlap).
Clocks: CPU 396 MHz, master 132 MHz, main 18.432 MHz
Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 14224
Kernel command line: console=ttyS0,115200 root=/dev/ram0 rw mtdparts=atmel_nand:32768K(local0),32768K(local1),32768K(local2),32768K(local3),32768K(local4),-(data) imageDevs=spi0.0,spi0.1 dflog=4980736,5242880,256,spi0.0 dflog=33292288,33554432,256,spi0.0 dflog=4980736,5242880,256,spi0.1 dflog=33292288,33554432,256,spi0.1 dflog=65536,131071,256,i2c-0.50
NR_IRQS:192
AT91: 96 gpio irqs in 3 banks
PID hash table entries: 256 (order: 8, 1024 bytes)
Console: colour dummy device 80x30
console [ttyS0] enabled
Dentry cache hash table entries: 8192 (order: 3, 32768 bytes)
Inode-cache hash table entries: 4096 (order: 2, 16384 bytes)
Memory: 56MB = 56MB total
Memory: 50800KB available (2688K code, 194K data, 104K init, 0K highmem)
Calibrating delay loop... 197.83 BogoMIPS (lpj=989184)
Mount-cache hash table entries: 512
CPU: Testing write buffer coherency: ok
net_namespace: 296 bytes
NET: Registered protocol family 16

 *** 3v3 and 5V0 PL disabled
<7>PM: Adding info for platform:i2c-gpio.0
*** GPIO i2c-0 driver
*** called MOD at91_add_device_i2c


 *** Rev 3 or greater board init.

*** Rev 3+ Mux enabled
<7>PM: Adding info for platform:atmel_spi.0
*** called MOD at91_add_device_i2c
AT91: Power Management
AT91: Starting after general reset
bio: create slab <bio-0> at 0
SCSI subsystem initialized
usbcore: registered new interface driver usbfs
usbcore: registered new interface driver hub
usbcore: registered new device driver usb
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 2048 (order: 2, 16384 bytes)
TCP bind hash table entries: 2048 (order: 1, 8192 bytes)
TCP: Hash tables configured (established 2048 bind 2048)
TCP reno registered
NET: Registered protocol family 1
Trying to unpack rootfs image as initramfs...
Freeing initrd memory: 2860K
JFFS2 version 2.2. (NAND) (SUMMARY)  © 2001-2006 Red Hat, Inc.
msgmni has been set to 104
io scheduler noop registered
io scheduler anticipatory registered (default)
atmel_usart.0: ttyS0 at MMIO 0xfefff200 (irq = 1) is a ATMEL_SERIAL
brd: module loaded
loop: module loaded
Driver 'sd' needs updating - please use bus_type methods
PPP generic driver version 2.4.2
tun: Universal TUN/TAP device driver, 1.6
tun: (C) 1999-2004 Max Krasnyansky <maxk@qualcomm.com>
macb macb: invalid hw address, using random
MACB_mii_bus: probed
eth0: Atmel MACB at 0xfffc4000 irq 21 (8e:00:2c:a2:1f:d8)
eth0: attached PHY driver [Generic PHY] (mii_bus:phy_addr=ffffffff:00, irq=-1)
impA7:probing 0x00800000 at 0x00000000
impA7:probing 0x00800000 at 0x10000000
NAND device: Manufacturer ID: 0x01, Chip ID: 0xac (AMD NAND 512MiB 1,8V 8-bit)
AT91 NAND: 8-bit, Software ECC
Scanning device for bad blocks
Bad eraseblock 2322 at 0x000012240000
1 Bad eraseblocks.
6 cmdlinepart partitions found on MTD device atmel_nand
Creating 6 MTD partitions on "atmel_nand":
0x000000000000-0x000002000000 : "local0"
mtd: Giving out device 0 to local0
0x000002000000-0x000004000000 : "local1"
mtd: Giving out device 1 to local1
0x000004000000-0x000006000000 : "local2"
mtd: Giving out device 2 to local2
0x000006000000-0x000008000000 : "local3"
mtd: Giving out device 3 to local3
0x000008000000-0x00000a000000 : "local4"
mtd: Giving out device 4 to local4
0x00000a000000-0x000020000000 : "data"
mtd: Giving out device 5 to data
atmel_spi atmel_spi.0: Atmel SPI Controller at 0xfffc8000 (irq 12).  17 CS lines
atmel_spi atmel_spi.1: Atmel SPI Controller at 0xfffcc000 (irq 13).  17 CS lines
ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
at91_ohci at91_ohci: AT91 OHCI
at91_ohci at91_ohci: new USB bus registered, assigned bus number 1
at91_ohci at91_ohci: irq 20, io mem 0x00500000
usb usb1: New USB device found, idVendor=1d6b, idProduct=0001
usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
usb usb1: Product: AT91 OHCI
usb usb1: Manufacturer: Linux 2.6.30.2 ohci_hcd
usb usb1: SerialNumber: at91
usb usb1: configuration #1 chosen from 1 choice
hub 1-0:1.0: USB hub found
hub 1-0:1.0: 2 ports detected
Initializing USB Mass Storage driver...
usbcore: registered new interface driver usb-storage
USB Mass Storage support registered.
udc: at91_udc version 3 May 2006
mice: PS/2 mouse device common for all mice
ds3234 spi1.8: Control Reg: 0x1c
ds3234 spi1.8: Ctrl/Stat Reg: 0x88
ds3234 spi1.8: rtc core: registered ds3234 as rtc0
i2c /dev entries driver
NAND Switched to alternate CS line
i2c-gpio i2c-gpio.0: using pins 55 (SDA) and 56 (SCL)
i2c-gpio i2c-gpio.1: using pins 81 (SDA) and 82 (SCL)
Linux video capture interface: v2.00
usbcore: registered new interface driver uvcvideo
USB Video Class driver (v0.1.0)
TCP cubic registered
NET: Registered protocol family 17
PM: no wakealarm-capable RTC driver is ready
ds3234 spi1.8: setting system clock to 2000-01-01 00:00:21 UTC (946684821)
Atmel MCI controller at 0xfffa8000 irq 9, 1 slots
atmel_mci atmel_mci: Atmel MCI controller at 0xfffa8000 irq 9, 1 slots
Freeing init memory: 104K
init.d: /etc/init.d/S00a_wd_tap
init.d: /etc/init.d/S00critical_data
init.d: /etc/init.d/S00loopback
init.d: /etc/init.d/S01logging
init.d: /etc/init.d/S01modules
Probing for dba hardware at 0-52
at24 0-0052: 16384 byte 24c128 EEPROM (read-only)
PolySat UHF Radio found at 0-0052
dba reg gpio val: 104
<1>reg_ready gpio val: 225
<1>txrx gpio val: 83
Hardware version: 0x0002
AX5042 Module Registered as "AX5042"
Probing for dbb hardware at 0-53
EEPROM read failure: No such device or address
No EEPROM found at 0-0053
EEPROM 0-0053 not found
Probing for -z hardware at 0-55
at24 0-0055: 16384 byte 24c128 EEPROM (read-only)
PolySat -Z i2c switch found at 0-0055
pca9548 module load.
Adding i2c mux device to bus 0
pca9548 0-0072: pca9548-i2c switch at your service!!!
Probing for -z-misc hardware at 10-54
EEPROM read failure: No such device or address
No EEPROM found at 10-0054
EEPROM 10-0054 not found
Probing for -z hardware at 11-54
at24 11-0054: 16384 byte 24c128 EEPROM (read-only)
PolySat Z panel found at 11-0054
Adding -Z devices to bus
Probing for +x hardware at 12-54
EEPROM read failure: No such device or address
No EEPROM found at 12-0054
EEPROM 12-0054 not found
Probing for boom0 hardware at 13-54
EEPROM read failure: No such device or address
No EEPROM found at 13-0054
EEPROM 13-0054 not found
Probing for +z hardware at 14-54
EEPROM read failure: No such device or address
No EEPROM found at 14-0054
EEPROM 14-0054 not found
Probing for +y hardware at 15-54
EEPROM read failure: No such device or address
No EEPROM found at 15-0054
EEPROM 15-0054 not found
Probing for -x hardware at 16-54
EEPROM read failure: No such device or address
No EEPROM found at 16-0054
EEPROM 16-0054 not found
Probing for -y hardware at 17-54
EEPROM read failure: No such device or address
No EEPROM found at 17-0054
EEPROM 17-0054 not found
Probing for pib hardware at 1-50
EEPROM read failure: No such device or address
No EEPROM found at 1-0050
EEPROM 1-0050 not found
Probing for pib hardware at 1-51
EEPROM read failure: No such device or address
No EEPROM found at 1-0051
EEPROM 1-0051 not found
Probing for pib hardware at 1-52
EEPROM read failure: No such device or address
No EEPROM found at 1-0052
EEPROM 1-0052 not found
Probing for pib hardware at 1-53
EEPROM read failure: No such device or address
No EEPROM found at 1-0053
EEPROM 1-0053 not found
Probing for +z hardware at 1-55
EEPROM read failure: No such device or address
No EEPROM found at 1-0055
EEPROM 1-0055 not found
init.d: /etc/init.d/S10auto_detect
init.d: /etc/init.d/S20urandom
init.d: /etc/init.d/S40network
init.d: /etc/init.d/S41ethernet
usb0: MAC 00:02:0a:01:a2:05
usb0: HOST MAC 00:02:0a:02:a2:05
g_ether gadget: Ethernet Gadget, version: Memorial Day 2008
g_ether gadget: g_ether ready
init.d: /etc/init.d/S42g_ethernet
init.d: /etc/init.d/S50nand
g_ether gadget: full speed config #1: CDC Ethernet (ECM)
init.d: /etc/init.d/S60usr_local
yaffs: dev is 32505861 name is "mtdblock5" rw
yaffs: passed flags ""
init.d: /etc/init.d/S61data
init.d: /etc/init.d/S62sdcard
init.d: /etc/init.d/S62z_patch_script
init.d: /etc/init.d/S63fakedate
Unable to enable pps interrupt
init.d: /etc/init.d/S64clksync
init.d: /etc/init.d/S70auto_detect
init.d: /etc/init.d/S80dropbear
init.d: /etc/init.d/S98log_cleaner
init.d:
Falcon ODE FSW Image
Default login is root/calpoly
Built: Mon Jan 28 17:04:45 MST 2019

buildroot login: Jan  1 00:00:08 sys_manager[867]: Warning: Option 'PROTECTION' not valid at line 57

Jan  1 00:00:08 sys_manager[867]: Warning: Option 'CMDOID' not valid at line 70

Jan  1 00:00:08 sys_manager[867]: Warning: Option 'GRPOID' not valid at line 72

Jan  1 00:00:08 sys_manager[867]: Warning: Option 'PROTECTION' not valid at line 74

root
Password: 
# cp\#d##d/data/s#atcomm.cfg/etcc/data/satcomm.cfg/etcp/data/satcomm.cfg/etc/data/satcomm.cfg/etc
-sh: cp/data/satcomm.cfg/etc: not found
# cd data
-sh: cd: can't cd to data
# # cd data# cp/data/satcomm.cfg/etc# cd data#######cd /data/
# ls
CubeSatDB.000.sqlite  ode_image             satcomm.cfg
dwnqs.dat             payload               watchdog.log
last_good_ode_image   payload_fsm_logs
lost+found            payload_fsm_queue
# cd sa#to\comm.c########comm.cfg
-sh: cd: can't cd to satcomm.cfg
# s#ls - ;###-l
total 50
-rw-r--r--    1 root     root         15360 Jan  1 00:00 CubeSatDB.000.sqlite
-rw-r--r--    1 root     root             0 Jan  1 00:00 dwnqs.dat
drwxrwxr-x    1 root     root          2048 Jan  1 00:04 last_good_ode_image
drwx------    1 root     root          2048 Jan  1  2000 lost+found
drwxrwxr-x    1 root     root          2048 Jan  1 00:01 ode_image
drwxr-xr-x    1 root     root          2048 Jan  1 00:04 payload
drwxr-xr-x    1 root     root          2048 Jan  1 00:08 payload_fsm_logs
drwxr-xr-x    1 root     root          2048 Jan  1 00:08 payload_fsm_queue
-rw-------    1 root     root          1860 Jan  1 00:12 satcomm.cfg
-rw-r--r--    1 root     root         21329 Jan  1 00:00 watchdog.log
# cd..
-sh: cd..: not found
# cp /data/sta##atcomm.cfg/etc
BusyBox v1.20.1 (2018-06-18 07:47:35 MDT) multi-call binary.

Usage: cp [OPTIONS] SOURCE... DEST

Copy SOURCE(s) to DEST

	-a	Same as -dpR
	-R,-r	Recurse
	-d,-P	Preserve symlinks (default if -R)
	-L	Follow all symlinks
	-H	Follow symlinks on command line
	-p	Preserve file attributes if possible
	-f	Overwrite
	-i	Prompt before overwrite
	-l,-s	Create (sym)links

# cd /data/
# ls
CubeSatDB.000.sqlite  ode_image             satcomm.cfg
dwnqs.dat             payload               watchdog.log
last_good_ode_image   payload_fsm_logs
lost+found            payload_fsm_queue
# cd ###cd..
-sh: cd..: not found
# cd ..
# cp /data/staco####atcomm/#.cfp/ctc###et#tc
BusyBox v1.20.1 (2018-06-18 07:47:35 MDT) multi-call binary.

Usage: cp [OPTIONS] SOURCE... DEST

Copy SOURCE(s) to DEST

	-a	Same as -dpR
	-R,-r	Recurse
	-d,-P	Preserve symlinks (default if -R)
	-L	Follow all symlinks
	-H	Follow symlinks on command line
	-p	Preserve file attributes if possible
	-f	Overwrite
	-i	Prompt before overwrite
	-l,-s	Create (sym)links

# satcomm
satcomm[2830]: Warning: Option 'NAME' not valid at line 61

Interface type: ax5042
satcomm[2830]: TODO: Adjusting Routing Tables...

satcomm[2830]: UHF reprogramming device 1
BoaCant skip auto-ranging...
rd R6, batch 1, serial 14; crystal: 15998121

SQ 1: Freq: 494985509, FEC: 0
N: 41477
Warning: using ideal crystal value.  probably incorrect.
Programming queue 1
libqnum: 1, 96
Auto-range: 0x5 in 0
done reprogramming 1 to 0x1D80E125
Set parareprogramming device 2
ms:Cant skip auto-ranging...
 
Carrier: 468000000.000000Q 2: Freq: 494985509, FEC: 0

Crystal: 15998121.000000
Bitrate: 9600
h: 1.000000
TMGCORRFRAC: 32
Encoding: NRZI+Scrambled
Modulation: FSK
FEC: Off
Framing: HDLC
CRC: CCITT
Programming queue 2
libqnum: 2, 96
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-range: 0x5 in 0
done reprogramming 2 to 0x1D80E125
Set parareprogramming device 3
ms:Cant skip auto-ranging...
 
Carrier: 468000000.000Q 3: Freq: 471704881, FEC: 0
000
Crystal: 15998121.000000
Bitrate: 9600
h: 1.000000
TMGCORRFRAC: 32
Encoding: NRZI+Scrambled
Modulation: FSK
FEC: Off
Framing: HDLC
CRC: CCITT
Programming queue 3
libqnum: 3, 96
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
reAuto-ranging failed (cnt: 0, reg: 0x2B)!
vootAuto-ranging failed (cnt: 0, reg: 0x2B)!

Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
#Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
haAuto-ranging failed (cnt: 0, reg: 0x2B)!
ltAuto-ranging failed (cnt: 0, reg: 0x2B)!

Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-range: 0x7 in 0
done reprogramming 3 to 0x1C1DA531
Set params: 
Carrier: 449800000.000000
Crystal: 15998121.000000
Bitrate: 9600
h: 1.reprogramming device 4
00000Cant skip auto-ranging...
0
TMGCORRFRAC: 32Q 4: Freq: 494985509, FEC: 0

Encoding: NRZI+Scrambled
Modulation: FSK
FEC: Off
Framing: HDLC
CRC: CCITT
Programming queue 4
libqnum: 4, 96
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
RomBOOT
Starting NoBrick-BS
Board Type... Intrepid 1.5
df reader init (0x0)...Spansion 256Mb
Boot device: SPI    chip id: 20C6:0E10:36BF:98CE:2CFF:7C71:3E3F:EF14
df reader init (0x0)...Spansion 256Mb
   chip id: 20C6:0E10:36BF:98CE:2CFF:7C71:3E3F:EF14
df reader init (0x1)...Spansion 256Mb
   chip id: 0CF6:8156:4FA1:439E:20DB:3F45:21C3:12CE
Loading part 2 of BS...
  using 0x0
Done

ChipID: 0x01AC

-E- No NandFlash detected !!!
bad i2c checksum: 0E00:00EA:0500:00EA
bad i2c checksum: 0500:00EA:0500:00EA
bad i2c checksum: 0500:00EA:2038:0000
bad i2c checksum: 0500:00EA:0500:00EA
bad i2c checksum: FEFF:FFEA:FEFF:FFEA
bad i2c checksum: FEFF:FFEA:FEFF:FFEA
bad i2c checksum: FEFF:FFEA:FEFF:FFEA
bad i2c checksum: FEFF:FFEA:0340:0000
i2c serial number: FEFF:FFEA:0340:0000
f1id UID match
f2id UID match

Board number: 0xA205
Board number: 
0x3
NAND to alternative
console=ttyS0,115200 root=/dev/ram0 rw mtdparts=atmel_nand:32768K(local0),32768K(local1),32768K(local2),32768K(local3),32768K(local4),-(data) imageDevs=spi0.0,spi0.1log_copy_kernel
Log: 0x00303B10
   [0x004C0000, 0x00500000): 0x00203824
Meta Data for Log: 0x00303B10
	memStart:      0x004C0000
	memStop:       0x00500000
	head:          0x004C0000
	tail:          0x004C3E00
	nextFreeSlot:  0x004C3F00
	nextSeqNum:    0x00000040
	write size:    0x00000100
Log: 0x00303B34
   [0x01FC0000, 0x02000000): 0x00203824
Meta Data for Log: 0x00303B34
	memStart:      0x01FC0000
	memStop:       0x02000000
	head:          0x01FC0000
	tail:          0x01FC3E00
	nextFreeSlot:  0x01FC3F00
	nextSeqNum:    0x00000040
	write size:    0x00000100
Log: 0x00303B58
   [0x004C0000, 0x00500000): 0x00203878
Meta Data for Log: 0x00303B58
	memStart:      0x004C0000
	memStop:       0x00500000
	head:          0x004C0000
	tail:          0x004C3E00
	nextFreeSlot:  0x004C3F00
	nextSeqNum:    0x00000040
	write size:    0x00000100
Log: 0x00303B7C
   [0x01FC0000, 0x02000000): 0x00203878
Meta Data for Log: 0x00303B7C
	memStart:      0x01FC0000
	memStop:       0x02000000
	head:          0x01FC0000
	tail:          0x01FC3E00
	nextFreeSlot:  0x01FC3F00
	nextSeqNum:    0x00000040
	write size:    0x00000100
Log: 0x00303BA0
   [0x00010000, 0x0001FFFF): 0x002038CC
Meta Data for Log: 0x00303BA0
	memStart:      0x00010000
	memStop:       0x0001FFFF
	head:          0x00010000
	tail:          0x00013E00
	nextFreeSlot:  0x00013F00
	nextSeqNum:    0x00000040
	write size:    0x00000100
Post Scan State: 
	reqBootKern:      0x0001
	reqBootFDT:    0x0001
	reqBootInitrd:    0x0001
	reqBootFS:        0x0001
	bootSeqNum:       0x00000007
	Kernel Table - 
	tabVers:      0x00000001
	   [0x0] - 
		vers:       0x0001
		offset:     0x00040000
		len:        0x0017AF8C
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        A2A2:79B9:82D1:C3F2:52BF:E10E:E3DD:FD33
		attemptCnt: 0x00000046
		successCnt: 0x00000046
	   [0x1] - 
		vers:       0x0001
		offset:     0x00500000
		len:        0x0017AF8C
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        A2A2:79B9:82D1:C3F2:52BF:E10E:E3DD:FD33
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x2] - empty
	   [0x3] - empty
	   [0x4] - empty
	   [0x5] - empty
	   [0x6] - empty
	FDT Table - 
	tabVers:      0x00000003
	   [0x0] - empty
	   [0x1] - empty
	   [0x2] - empty
	   [0x3] - empty
	   [0x4] - empty
	   [0x5] - empty
	   [0x6] - empty
	Initrd Table - 
	tabVers:      0x00000002
	   [0x00] - 
		vers:       0x0001
		offset:     0x001C0000
		len:        0x002CB679
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        EBB4:3B81:3AAD:4609:61CA:0FD4:4333:CF90
		attemptCnt: 0x00000046
		successCnt: 0x00000046
	   [0x01] - 
		vers:       0x0001
		offset:     0x00680000
		len:        0x002CB679
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		md5:        EBB4:3B81:3AAD:4609:61CA:0FD4:4333:CF90
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x02] - empty
	   [0x03] - empty
	   [0x04] - empty
	   [0x05] - empty
	   [0x06] - empty
	FS Table - 
	tabVers:      0x00000006
	   [0x000] - 
		vers:       0x0001
		offset:     0x00000000
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x001] - 
		vers:       0x0001
		offset:     0x00000001
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x002] - 
		vers:       0x0001
		offset:     0x00000002
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x003] - 
		vers:       0x0001
		offset:     0x00000003
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x004] - 
		vers:       0x0001
		offset:     0x00000004
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x005] - 
		vers:       0x0001
		offset:     0x00000005
		len:        0x00000000
		compat:     0xFFFE, 0xFFFE, 0xFFFE, 0xFFFE
		attemptCnt: 0x00000000
		successCnt: 0x00000000
	   [0x006] - empty
	   [0x007] - empty
	   [0x008] - empty
	   [0x009] - empty
	   [0x00A] - empty
	   [0x00B] - empty
	   [0x00C] - empty
	   [0x00D] - empty
Evaluating MD5 File Table 0x0/0x0: 
	version compat check: 
	minVers: 0xFFFE
	myVers: 0x0001
	maxVers: 0x0001
    Evaluating MD5 File Table 0x1/0x0: 
empty
	version compat check: 
	minVers: 0xFFFE
	myVers: 0x0000
	maxVers: 0x0001
        Evaluating MD5 File Table 0x2/0x0: 
	version compat check: 
	minVers: 0x0000
	myVers: 0x0001
	maxVers: 0x0001
Loading file[0x2/0x0] from 0x001C0000 len 0x002CB679 to 0x20800000
good
good
Loading file[0x0/0x0] from 0x00040000 len 0x0017AF8C to 0x20008000
good
Attempting boot:
	kernel 0x0
	initrd 0x0
	rootfs 0x0
Write to 0x004C3F00 successful
Write to 0x01FC3F00 successful
Write to 0x004C3F00 successful
Write to 0x01FC3F00 successful
Write to 0x00013F00 successful
Uncompressing Linux...
.............................................................................................. done, booting the kernel.
Linux version 2.6.30.2 (falconode@falconode-HP-ProBook-640-G3) (gcc version 4.7.3 (Buildroot 2012.05-g08977ee) ) #1 Mon Jan 28 17:04:34 MST 2019
CPU: ARM926EJ-S [41069265] revision 5 (ARMv5TEJ), cr=00053177
CPU: VIVT data cache, VIVT instruction cache
Machine: PolySat Avionics Board, version 1
Memory policy: ECC disabled, Data cache writeback
Ignoring RAM at 00200000-00203fff (vmalloc region overlap).
Ignoring RAM at 00300000-00303fff (vmalloc region overlap).
Clocks: CPU 396 MHz, master 132 MHz, main 18.432 MHz
Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 14224
Kernel command line: console=ttyS0,115200 root=/dev/ram0 rw mtdparts=atmel_nand:32768K(local0),32768K(local1),32768K(local2),32768K(local3),32768K(local4),-(data) imageDevs=spi0.0,spi0.1 dflog=4980736,5242880,256,spi0.0 dflog=33292288,33554432,256,spi0.0 dflog=4980736,5242880,256,spi0.1 dflog=33292288,33554432,256,spi0.1 dflog=65536,131071,256,i2c-0.50
NR_IRQS:192
AT91: 96 gpio irqs in 3 banks
PID hash table entries: 256 (order: 8, 1024 bytes)
Console: colour dummy device 80x30
console [ttyS0] enabled
Dentry cache hash table entries: 8192 (order: 3, 32768 bytes)
Inode-cache hash table entries: 4096 (order: 2, 16384 bytes)
Memory: 56MB = 56MB total
Memory: 50800KB available (2688K code, 194K data, 104K init, 0K highmem)
Calibrating delay loop... 197.83 BogoMIPS (lpj=989184)
Mount-cache hash table entries: 512
CPU: Testing write buffer coherency: ok
net_namespace: 296 bytes
NET: Registered protocol family 16

 *** 3v3 and 5V0 PL disabled
<7>PM: Adding info for platform:i2c-gpio.0
*** GPIO i2c-0 driver
*** called MOD at91_add_device_i2c


 *** Rev 3 or greater board init.

*** Rev 3+ Mux enabled
<7>PM: Adding info for platform:atmel_spi.0
*** called MOD at91_add_device_i2c
AT91: Power Management
AT91: Starting after general reset
bio: create slab <bio-0> at 0
SCSI subsystem initialized
usbcore: registered new interface driver usbfs
usbcore: registered new interface driver hub
usbcore: registered new device driver usb
NET: Registered protocol family 2
IP route cache hash table entries: 1024 (order: 0, 4096 bytes)
TCP established hash table entries: 2048 (order: 2, 16384 bytes)
TCP bind hash table entries: 2048 (order: 1, 8192 bytes)
TCP: Hash tables configured (established 2048 bind 2048)
TCP reno registered
NET: Registered protocol family 1
Trying to unpack rootfs image as initramfs...
Freeing initrd memory: 2860K
JFFS2 version 2.2. (NAND) (SUMMARY)  © 2001-2006 Red Hat, Inc.
msgmni has been set to 104
io scheduler noop registered
io scheduler anticipatory registered (default)
atmel_usart.0: ttyS0 at MMIO 0xfefff200 (irq = 1) is a ATMEL_SERIAL
brd: module loaded
loop: module loaded
Driver 'sd' needs updating - please use bus_type methods
PPP generic driver version 2.4.2
tun: Universal TUN/TAP device driver, 1.6
tun: (C) 1999-2004 Max Krasnyansky <maxk@qualcomm.com>
macb macb: invalid hw address, using random
MACB_mii_bus: probed
eth0: Atmel MACB at 0xfffc4000 irq 21 (26:f9:be:25:33:3f)
eth0: attached PHY driver [Generic PHY] (mii_bus:phy_addr=ffffffff:00, irq=-1)
impA7:probing 0x00800000 at 0x00000000
impA7:probing 0x00800000 at 0x10000000
NAND device: Manufacturer ID: 0x01, Chip ID: 0xac (AMD NAND 512MiB 1,8V 8-bit)
AT91 NAND: 8-bit, Software ECC
Scanning device for bad blocks
Bad eraseblock 2322 at 0x000012240000
1 Bad eraseblocks.
6 cmdlinepart partitions found on MTD device atmel_nand
Creating 6 MTD partitions on "atmel_nand":
0x000000000000-0x000002000000 : "local0"
mtd: Giving out device 0 to local0
0x000002000000-0x000004000000 : "local1"
mtd: Giving out device 1 to local1
0x000004000000-0x000006000000 : "local2"
mtd: Giving out device 2 to local2
0x000006000000-0x000008000000 : "local3"
mtd: Giving out device 3 to local3
0x000008000000-0x00000a000000 : "local4"
mtd: Giving out device 4 to local4
0x00000a000000-0x000020000000 : "data"
mtd: Giving out device 5 to data
atmel_spi atmel_spi.0: Atmel SPI Controller at 0xfffc8000 (irq 12).  17 CS lines
atmel_spi atmel_spi.1: Atmel SPI Controller at 0xfffcc000 (irq 13).  17 CS lines
ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
at91_ohci at91_ohci: AT91 OHCI
at91_ohci at91_ohci: new USB bus registered, assigned bus number 1
at91_ohci at91_ohci: irq 20, io mem 0x00500000
usb usb1: New USB device found, idVendor=1d6b, idProduct=0001
usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
usb usb1: Product: AT91 OHCI
usb usb1: Manufacturer: Linux 2.6.30.2 ohci_hcd
usb usb1: SerialNumber: at91
usb usb1: configuration #1 chosen from 1 choice
hub 1-0:1.0: USB hub found
hub 1-0:1.0: 2 ports detected
Initializing USB Mass Storage driver...
usbcore: registered new interface driver usb-storage
USB Mass Storage support registered.
udc: at91_udc version 3 May 2006
mice: PS/2 mouse device common for all mice
ds3234 spi1.8: Control Reg: 0x1c
ds3234 spi1.8: Ctrl/Stat Reg: 0x88
ds3234 spi1.8: rtc core: registered ds3234 as rtc0
i2c /dev entries driver
NAND Switched to alternate CS line
i2c-gpio i2c-gpio.0: using pins 55 (SDA) and 56 (SCL)
i2c-gpio i2c-gpio.1: using pins 81 (SDA) and 82 (SCL)
Linux video capture interface: v2.00
usbcore: registered new interface driver uvcvideo
USB Video Class driver (v0.1.0)
TCP cubic registered
NET: Registered protocol family 17
PM: no wakealarm-capable RTC driver is ready
ds3234 spi1.8: setting system clock to 2010-01-01 00:06:14 UTC (1262304374)
Atmel MCI controller at 0xfffa8000 irq 9, 1 slots
atmel_mci atmel_mci: Atmel MCI controller at 0xfffa8000 irq 9, 1 slots
Freeing init memory: 104K
init.d: /etc/init.d/S00a_wd_tap
init.d: /etc/init.d/S00critical_data
init.d: /etc/init.d/S00loopback
init.d: /etc/init.d/S01logging
init.d: /etc/init.d/S01modules
Probing for dba hardware at 0-52
at24 0-0052: 16384 byte 24c128 EEPROM (read-only)
PolySat UHF Radio found at 0-0052
dba reg gpio val: 104
<1>reg_ready gpio val: 225
<1>txrx gpio val: 83
Hardware version: 0x0002
AX5042 Module Registered as "AX5042"
Probing for dbb hardware at 0-53
EEPROM read failure: No such device or address
No EEPROM found at 0-0053
EEPROM 0-0053 not found
Probing for -z hardware at 0-55
at24 0-0055: 16384 byte 24c128 EEPROM (read-only)
PolySat -Z i2c switch found at 0-0055
pca9548 module load.
Adding i2c mux device to bus 0
pca9548 0-0072: pca9548-i2c switch at your service!!!
Probing for -z-misc hardware at 10-54
EEPROM read failure: No such device or address
No EEPROM found at 10-0054
EEPROM 10-0054 not found
Probing for -z hardware at 11-54
at24 11-0054: 16384 byte 24c128 EEPROM (read-only)
PolySat Z panel found at 11-0054
Adding -Z devices to bus
Probing for +x hardware at 12-54
EEPROM read failure: No such device or address
No EEPROM found at 12-0054
EEPROM 12-0054 not found
Probing for boom0 hardware at 13-54
EEPROM read failure: No such device or address
No EEPROM found at 13-0054
EEPROM 13-0054 not found
Probing for +z hardware at 14-54
EEPROM read failure: No such device or address
No EEPROM found at 14-0054
EEPROM 14-0054 not found
Probing for +y hardware at 15-54
EEPROM read failure: No such device or address
No EEPROM found at 15-0054
EEPROM 15-0054 not found
Probing for -x hardware at 16-54
EEPROM read failure: No such device or address
No EEPROM found at 16-0054
EEPROM 16-0054 not found
Probing for -y hardware at 17-54
EEPROM read failure: No such device or address
No EEPROM found at 17-0054
EEPROM 17-0054 not found
Probing for pib hardware at 1-50
EEPROM read failure: No such device or address
No EEPROM found at 1-0050
EEPROM 1-0050 not found
Probing for pib hardware at 1-51
EEPROM read failure: No such device or address
No EEPROM found at 1-0051
EEPROM 1-0051 not found
Probing for pib hardware at 1-52
EEPROM read failure: No such device or address
No EEPROM found at 1-0052
EEPROM 1-0052 not found
Probing for pib hardware at 1-53
EEPROM read failure: No such device or address
No EEPROM found at 1-0053
EEPROM 1-0053 not found
Probing for +z hardware at 1-55
EEPROM read failure: No such device or address
No EEPROM found at 1-0055
EEPROM 1-0055 not found
init.d: /etc/init.d/S10auto_detect
init.d: /etc/init.d/S20urandom
init.d: /etc/init.d/S40network
init.d: /etc/init.d/S41ethernet
usb0: MAC 00:02:0a:01:a2:05
usb0: HOST MAC 00:02:0a:02:a2:05
g_ether gadget: Ethernet Gadget, version: Memorial Day 2008
g_ether gadget: g_ether ready
init.d: /etc/init.d/S42g_ethernet
init.d: /etc/init.d/S50nand
g_ether gadget: full speed config #1: CDC Ethernet (ECM)
init.d: /etc/init.d/S60usr_local
yaffs: dev is 32505861 name is "mtdblock5" rw
yaffs: passed flags ""
init.d: /etc/init.d/S61data
init.d: /etc/init.d/S62sdcard
init.d: /etc/init.d/S62z_patch_script
init.d: /etc/init.d/S63fakedate
Unable to enable pps interrupt
init.d: /etc/init.d/S64clksync
init.d: /etc/init.d/S70auto_detect
init.d: /etc/init.d/S80dropbear
init.d: /etc/init.d/S98log_cleaner
init.d:
Falcon ODE FSW Image
Default login is root/calpoly
Built: Mon Jan 28 17:04:45 MST 2019

buildroot login: Jan  1 00:06:35 sys_manager[867]: Warning: Option 'PROTECTION' not valid at line 57

Jan  1 00:06:35 sys_manager[867]: Warning: Option 'CMDOID' not valid at line 70

Jan  1 00:06:35 sys_manager[867]: Warning: Option 'GRPOID' not valid at line 72

Jan  1 00:06:35 sys_manager[867]: Warning: Option 'PROTECTION' not valid at line 74

root
Password: 
# pwd
/root
# vi /etc/inittab
# /etc/inittab
#
# Copyright (C) 2001 Erik Andersen <andersen@codepoet.org>
#
# Note: BusyBox init doesn't support runlevels.  The runlevels field is
# completely ignored by BusyBox init. If you want runlevels, use
# sysvinit.
#
# Format for each entry: <id>:<runlevels>:<action>:<process>
#
# id        == tty to run on, or empty for /dev/console
# runlevels == ignored
# action    == one of sysinit, respawn, askfirst, wait, and once
# process   == program to run

# Startup the system
null::sysinit:/bin/mount -t proc proc /proc
null::sysinit:/bin/mkdir -p /dev/pts
null::sysinit:/bin/mount -t devpts devpts /dev/pts
null::sysinit:/bin/mount -a
null::sysinit:/bin/hostname -F /etc/hostname
null::sysinit:/bin/mount -t sysfs sysfs /sys
null::sysinit:/bin/mkdir -p /dev/shm
null::sysinit:/sbin/mdev -s

# now run any rc scripts
null::sysinit:/etc/init.d/rcS
#null::sysinit:/etc/mount_usr_local.sh
# Keep this as the last sysinit line.  Should force loading of /usr/local/etc/inittab
null::sysinit:/bin/kill -HUP 1

# Put a getty on the serial port
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL
# Put a getty (login session) on backup USB-serial port.  Nice when ttyS0 is
#  needed for other purposes
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL

null::respawn:/bin/nice -n -10 /usr/bin/watchdog.sh
null::respawn:/bin/nice -n -5 /usr/sbin/sys_manager
null::respawn:/bin/nice -n -3 /usr/sbin/log_cleaner
null::respawn:/bin/nice -n -1 /usr/sbin/inetd -f
null::respawn:/bin/nice -n -3 /usr/bin/filemgr
null::respawn:/usr/sbin/clksync 2
null::respawn:/usr/sbin/crond -f

# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot

# Stuff to do before rebooting
null::shutdown:/etc/init.d/rcK
null::shutdown:/bin/umount -a -r
null::shutdown:/sbin/swapoff -a
~
~
~
~- /etc/inittab 1/52 1%
- /etc/inittab 2/52 3%
- /etc/inittab 3/52 5%
- /etc/inittab 4/52 7%
- /etc/inittab 5/52 9%
- /etc/inittab 6/52 11%
- /etc/inittab 7/52 13%
- /etc/inittab 8/52 15%
- /etc/inittab 9/52 17%
- /etc/inittab 10/52 19%
- /etc/inittab 11/52 21%
- /etc/inittab 12/52 23%
- /etc/inittab 13/52 25%
- /etc/inittab 14/52 26%
- /etc/inittab 15/52 28%
- /etc/inittab 16/52 30%
- /etc/inittab 17/52 32%
- /etc/inittab 18/52 34%
- /etc/inittab 19/52 36%
- /etc/inittab 20/52 38%
- /etc/inittab 21/52 40%
- /etc/inittab 22/52 42%
- /etc/inittab 23/52 44%
- /etc/inittab 24/52 46%
- /etc/inittab 25/52 48%
- /etc/inittab 26/52 50%
- /etc/inittab 27/52 51%
- /etc/inittab 28/52 53%
- /etc/inittab 29/52 55%
- /etc/inittab 30/52 57%
- /etc/inittab 31/52 59%
- /etc/inittab 32/52 61%
- /etc/inittab 33/52 63%
- /etc/inittab 34/52 65%
- /etc/inittab 35/52 67%
- /etc/inittab 36/52 69%
- /etc/inittab 37/52 71%
- /etc/inittab 38/52 73%nnunulnullnull:dog.sh - /etc/inittab [Modified] 38/52 73%og.sh g.sh .sh tc.sh c.sh .sh sh Delete 0 lines (1 chars) using [D]- /etc/inittab [Modified] 38/52 73%.hPut 0 lines (1 chars) from [D]- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%'!' is not implemented- /etc/inittab [Modified] 38/52 73%'Q' is not implemented- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%'!' is not implemented- /etc/inittab [Modified] 38/52 73%'!' is not implemented- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%'!' is not implemented- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%'q' is not implemented- /etc/inittab [Modified] 38/52 73%.h h  #- /etc/inittab [Modified] 38/52 73%I /etc/inittab [Modified] 38/52 73% 
w                                                  5 /usr/sbin/sys_manag3 /usr/sbin/log_cleaner1 /usr/sbin/inetd -fbin/nice -n -3 /usr/bin/filemgrlksync 2
null::respawn:/usr/sbin/crond -f
                                     
# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot
                              
# Stuff to do before rebootingetc/init.d/rcK  bin/umount -a -r
null::shutdown:/sbin/swapoff -aI /etc/inittab [Modified] 39/53 73%
I /etc/inittab [Modified] 40/53 75%I /etc/inittab [Modified] 39/53 73%I /etc/inittab [Modified] 38/53 71%nnunulnullnull:- /etc/inittab [Modified] 38/53 71%
- /etc/inittab [Modified] 39/53 73%wI /etc/inittab [Modified] 39/53 73%wawawaawaawaaawaaawaa waawa waw w - /etc/inittab [Modified] 39/53 73%:q!- /etc/inittab [Modified] 39/53 73%# # vi /etc/inittab
# /etc/inittab
#
# Copyright (C) 2001 Erik Andersen <andersen@codepoet.org>
#
# Note: BusyBox init doesn't support runlevels.  The runlevels field is
# completely ignored by BusyBox init. If you want runlevels, use
# sysvinit.
#
# Format for each entry: <id>:<runlevels>:<action>:<process>
#
# id        == tty to run on, or empty for /dev/console
# runlevels == ignored
# action    == one of sysinit, respawn, askfirst, wait, and once
# process   == program to run

# Startup the system
null::sysinit:/bin/mount -t proc proc /proc
null::sysinit:/bin/mkdir -p /dev/pts
null::sysinit:/bin/mount -t devpts devpts /dev/pts
null::sysinit:/bin/mount -a
null::sysinit:/bin/hostname -F /etc/hostname
null::sysinit:/bin/mount -t sysfs sysfs /sys
null::sysinit:/bin/mkdir -p /dev/shm
null::sysinit:/sbin/mdev -s

# now run any rc scripts
null::sysinit:/etc/init.d/rcS
#null::sysinit:/etc/mount_usr_local.sh
# Keep this as the last sysinit line.  Should force loading of /usr/local/etc/inittab
null::sysinit:/bin/kill -HUP 1

# Put a getty on the serial port
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL
# Put a getty (login session) on backup USB-serial port.  Nice when ttyS0 is
#  needed for other purposes
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL

null::respawn:/bin/nice -n -10 /usr/bin/watchdog.sh
null::respawn:/bin/nice -n -5 /usr/sbin/sys_manager
null::respawn:/bin/nice -n -3 /usr/sbin/log_cleaner
null::respawn:/bin/nice -n -1 /usr/sbin/inetd -f
null::respawn:/bin/nice -n -3 /usr/bin/filemgr
null::respawn:/usr/sbin/clksync 2
null::respawn:/usr/sbin/crond -f

# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot

# Stuff to do before rebooting
null::shutdown:/etc/init.d/rcK
null::shutdown:/bin/umount -a -r
null::shutdown:/sbin/swapoff -a
~
~
~
~- /etc/inittab 1/52 1%#- /etc/inittab 1/52 1%:w!"/etc/inittab" 52L, 1800C- /etc/inittab 1/52 1%
- /etc/inittab 2/52 3%
- /etc/inittab 3/52 5%
- /etc/inittab 4/52 7%- /etc/inittab 3/52 5%- /etc/inittab 2/52 3%
- /etc/inittab 3/52 5%
- /etc/inittab 4/52 7%
- /etc/inittab 5/52 9%
- /etc/inittab 6/52 11%#- /etc/inittab 6/52 11%:q!- /etc/inittab 6/52 11%# 
# 
# 
# 
# 
# 
# cp /da# cp /data/sat# cp /data/satcomm.cfg /etc
# vi /etc/initt# vi /etc/inittab 
# /etc/inittab
#
# Copyright (C) 2001 Erik Andersen <andersen@codepoet.org>
#
# Note: BusyBox init doesn't support runlevels.  The runlevels field is
# completely ignored by BusyBox init. If you want runlevels, use
# sysvinit.
#
# Format for each entry: <id>:<runlevels>:<action>:<process>
#
# id        == tty to run on, or empty for /dev/console
# runlevels == ignored
# action    == one of sysinit, respawn, askfirst, wait, and once
# process   == program to run

# Startup the system
null::sysinit:/bin/mount -t proc proc /proc
null::sysinit:/bin/mkdir -p /dev/pts
null::sysinit:/bin/mount -t devpts devpts /dev/pts
null::sysinit:/bin/mount -a
null::sysinit:/bin/hostname -F /etc/hostname
null::sysinit:/bin/mount -t sysfs sysfs /sys
null::sysinit:/bin/mkdir -p /dev/shm
null::sysinit:/sbin/mdev -s

# now run any rc scripts
null::sysinit:/etc/init.d/rcS
#null::sysinit:/etc/mount_usr_local.sh
# Keep this as the last sysinit line.  Should force loading of /usr/local/etc/inittab
null::sysinit:/bin/kill -HUP 1

# Put a getty on the serial port
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL
# Put a getty (login session) on backup USB-serial port.  Nice when ttyS0 is
#  needed for other purposes
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL

null::respawn:/bin/nice -n -10 /usr/bin/watchdog.sh
null::respawn:/bin/nice -n -5 /usr/sbin/sys_manager
null::respawn:/bin/nice -n -3 /usr/sbin/log_cleaner
null::respawn:/bin/nice -n -1 /usr/sbin/inetd -f
null::respawn:/bin/nice -n -3 /usr/bin/filemgr
null::respawn:/usr/sbin/clksync 2
null::respawn:/usr/sbin/crond -f

# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot

# Stuff to do before rebooting
null::shutdown:/etc/init.d/rcK
null::shutdown:/bin/umount -a -r
null::shutdown:/sbin/swapoff -a
~
~
~
~- /etc/inittab 1/52 1%
- /etc/inittab 2/52 3%
- /etc/inittab 3/52 5%
- /etc/inittab 4/52 7%
- /etc/inittab 5/52 9%
- /etc/inittab 6/52 11%
- /etc/inittab 7/52 13%
- /etc/inittab 8/52 15%
- /etc/inittab 9/52 17%
- /etc/inittab 10/52 19%
- /etc/inittab 11/52 21%
- /etc/inittab 12/52 23%
- /etc/inittab 13/52 25%
- /etc/inittab 14/52 26%
- /etc/inittab 15/52 28%
- /etc/inittab 16/52 30%
- /etc/inittab 17/52 32%
- /etc/inittab 18/52 34%
- /etc/inittab 19/52 36%
- /etc/inittab 20/52 38%
- /etc/inittab 21/52 40%
- /etc/inittab 22/52 42%
- /etc/inittab 23/52 44%
- /etc/inittab 24/52 46%
- /etc/inittab 25/52 48%
- /etc/inittab 26/52 50%
- /etc/inittab 27/52 51%
- /etc/inittab 28/52 53%
- /etc/inittab 29/52 55%
- /etc/inittab 30/52 57%
- /etc/inittab 31/52 59%
- /etc/inittab 32/52 61%
- /etc/inittab 33/52 63%
- /etc/inittab 34/52 65%
- /etc/inittab 35/52 67%
- /etc/inittab 36/52 69%
- /etc/inittab 37/52 71%
- /etc/inittab 38/52 73%
- /etc/inittab 39/52 75%- /etc/inittab 38/52 73%nnunulnullnull:#- /etc/inittab 38/52 73%:ik# #'i' is not implemented- /etc/inittab 38/52 73%.sh Delete 0 lines (1 chars) using [D]- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%:q!- /etc/inittab [Modified] 38/52 73%# # vi /etc/inittab 
# /etc/inittab
#
# Copyright (C) 2001 Erik Andersen <andersen@codepoet.org>
#
# Note: BusyBox init doesn't support runlevels.  The runlevels field is
# completely ignored by BusyBox init. If you want runlevels, use
# sysvinit.
#
# Format for each entry: <id>:<runlevels>:<action>:<process>
#
# id        == tty to run on, or empty for /dev/console
# runlevels == ignored
# action    == one of sysinit, respawn, askfirst, wait, and once
# process   == program to run

# Startup the system
null::sysinit:/bin/mount -t proc proc /proc
null::sysinit:/bin/mkdir -p /dev/pts
null::sysinit:/bin/mount -t devpts devpts /dev/pts
null::sysinit:/bin/mount -a
null::sysinit:/bin/hostname -F /etc/hostname
null::sysinit:/bin/mount -t sysfs sysfs /sys
null::sysinit:/bin/mkdir -p /dev/shm
null::sysinit:/sbin/mdev -s

# now run any rc scripts
null::sysinit:/etc/init.d/rcS
#null::sysinit:/etc/mount_usr_local.sh
# Keep this as the last sysinit line.  Should force loading of /usr/local/etc/inittab
null::sysinit:/bin/kill -HUP 1

# Put a getty on the serial port
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL
# Put a getty (login session) on backup USB-serial port.  Nice when ttyS0 is
#  needed for other purposes
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL

null::respawn:/bin/nice -n -10 /usr/bin/watchdog.sh
null::respawn:/bin/nice -n -5 /usr/sbin/sys_manager
null::respawn:/bin/nice -n -3 /usr/sbin/log_cleaner
null::respawn:/bin/nice -n -1 /usr/sbin/inetd -f
null::respawn:/bin/nice -n -3 /usr/bin/filemgr
null::respawn:/usr/sbin/clksync 2
null::respawn:/usr/sbin/crond -f

# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot

# Stuff to do before rebooting
null::shutdown:/etc/init.d/rcK
null::shutdown:/bin/umount -a -r
null::shutdown:/sbin/swapoff -a
~
~
~
~- /etc/inittab 1/52 1%
- /etc/inittab 2/52 3%
- /etc/inittab 3/52 5%
- /etc/inittab 4/52 7%
- /etc/inittab 5/52 9%
- /etc/inittab 6/52 11%
- /etc/inittab 7/52 13%
- /etc/inittab 8/52 15%
- /etc/inittab 9/52 17%
- /etc/inittab 10/52 19%
- /etc/inittab 11/52 21%
- /etc/inittab 12/52 23%
- /etc/inittab 13/52 25%
- /etc/inittab 14/52 26%
- /etc/inittab 15/52 28%
- /etc/inittab 16/52 30%
- /etc/inittab 17/52 32%
- /etc/inittab 18/52 34%
- /etc/inittab 19/52 36%
- /etc/inittab 20/52 38%
- /etc/inittab 21/52 40%
- /etc/inittab 22/52 42%
- /etc/inittab 23/52 44%
- /etc/inittab 24/52 46%
- /etc/inittab 25/52 48%
- /etc/inittab 26/52 50%
- /etc/inittab 27/52 51%
- /etc/inittab 28/52 53%
- /etc/inittab 29/52 55%
- /etc/inittab 30/52 57%
- /etc/inittab 31/52 59%
- /etc/inittab 32/52 61%
- /etc/inittab 33/52 63%
- /etc/inittab 34/52 65%
- /etc/inittab 35/52 67%
- /etc/inittab 36/52 69%
- /etc/inittab 37/52 71%
- /etc/inittab 38/52 73%
- /etc/inittab 39/52 75%
- /etc/inittab 40/52 76%
- /etc/inittab 41/52 78%
- /etc/inittab 42/52 80%
- /etc/inittab 43/52 82%- /etc/inittab 42/52 80%- /etc/inittab 41/52 78%- /etc/inittab 40/52 76%- /etc/inittab 39/52 75%- /etc/inittab 38/52 73%- /etc/inittab 37/52 71%- /etc/inittab 36/52 69%- /etc/inittab 35/52 67%- /etc/inittab 34/52 65%
- /etc/inittab 35/52 67%
- /etc/inittab 36/52 69%
- /etc/inittab 37/52 71%
- /etc/inittab 38/52 73%nnunulnullnull:I /etc/inittab 38/52 73%watchdog.shI /etc/inittab [Modified] 38/52 73%dwatchdog.shtwatchdog.shawatchdog.shpwatchdog.sh- /etc/inittab [Modified] 38/52 73%watchdog.sh atchdog.sh tchdog.sh chdog.sh hdog.sh dog.sh og.sh g.sh .sh sh h  #- /etc/inittab [Modified] 38/52 73%#- /etc/inittab [Modified] 38/52 73%I /etc/inittab [Modified] 38/52 73%apa - /etc/inittab [Modified] 38/52 73%:wq!"/etc/inittab" 52L, 1794C# ## vi /etc/inittab 
# /etc/inittab
#
# Copyright (C) 2001 Erik Andersen <andersen@codepoet.org>
#
# Note: BusyBox init doesn't support runlevels.  The runlevels field is
# completely ignored by BusyBox init. If you want runlevels, use
# sysvinit.
#
# Format for each entry: <id>:<runlevels>:<action>:<process>
#
# id        == tty to run on, or empty for /dev/console
# runlevels == ignored
# action    == one of sysinit, respawn, askfirst, wait, and once
# process   == program to run

# Startup the system
null::sysinit:/bin/mount -t proc proc /proc
null::sysinit:/bin/mkdir -p /dev/pts
null::sysinit:/bin/mount -t devpts devpts /dev/pts
null::sysinit:/bin/mount -a
null::sysinit:/bin/hostname -F /etc/hostname
null::sysinit:/bin/mount -t sysfs sysfs /sys
null::sysinit:/bin/mkdir -p /dev/shm
null::sysinit:/sbin/mdev -s

# now run any rc scripts
null::sysinit:/etc/init.d/rcS
#null::sysinit:/etc/mount_usr_local.sh
# Keep this as the last sysinit line.  Should force loading of /usr/local/etc/inittab
null::sysinit:/bin/kill -HUP 1

# Put a getty on the serial port
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL
# Put a getty (login session) on backup USB-serial port.  Nice when ttyS0 is
#  needed for other purposes
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL

null::respawn:/bin/nice -n -10 /usr/bin/wdtap
null::respawn:/bin/nice -n -5 /usr/sbin/sys_manager
null::respawn:/bin/nice -n -3 /usr/sbin/log_cleaner
null::respawn:/bin/nice -n -1 /usr/sbin/inetd -f
null::respawn:/bin/nice -n -3 /usr/bin/filemgr
null::respawn:/usr/sbin/clksync 2
null::respawn:/usr/sbin/crond -f

# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot

# Stuff to do before rebooting
null::shutdown:/etc/init.d/rcK
null::shutdown:/bin/umount -a -r
null::shutdown:/sbin/swapoff -a
~
~
~
~- /etc/inittab 1/52 1%#- /etc/inittab 1/52 1%:q!- /etc/inittab 1/52 1%# ls =-#\##-l /usr/bin/wd*&|###*
-rwxrwxr-x    1 root     root          3556 Jan 29  2019 /usr/bin/wd_tap
# # ls -l /usr/bin/wd*# vi /etc/inittab 
# /etc/inittab
#
# Copyright (C) 2001 Erik Andersen <andersen@codepoet.org>
#
# Note: BusyBox init doesn't support runlevels.  The runlevels field is
# completely ignored by BusyBox init. If you want runlevels, use
# sysvinit.
#
# Format for each entry: <id>:<runlevels>:<action>:<process>
#
# id        == tty to run on, or empty for /dev/console
# runlevels == ignored
# action    == one of sysinit, respawn, askfirst, wait, and once
# process   == program to run

# Startup the system
null::sysinit:/bin/mount -t proc proc /proc
null::sysinit:/bin/mkdir -p /dev/pts
null::sysinit:/bin/mount -t devpts devpts /dev/pts
null::sysinit:/bin/mount -a
null::sysinit:/bin/hostname -F /etc/hostname
null::sysinit:/bin/mount -t sysfs sysfs /sys
null::sysinit:/bin/mkdir -p /dev/shm
null::sysinit:/sbin/mdev -s

# now run any rc scripts
null::sysinit:/etc/init.d/rcS
#null::sysinit:/etc/mount_usr_local.sh
# Keep this as the last sysinit line.  Should force loading of /usr/local/etc/inittab
null::sysinit:/bin/kill -HUP 1

# Put a getty on the serial port
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL
# Put a getty (login session) on backup USB-serial port.  Nice when ttyS0 is
#  needed for other purposes
ttyS0::respawn:/sbin/getty -L ttyS0 115200 vt100 # GENERIC_SERIAL

null::respawn:/bin/nice -n -10 /usr/bin/wdtap
null::respawn:/bin/nice -n -5 /usr/sbin/sys_manager
null::respawn:/bin/nice -n -3 /usr/sbin/log_cleaner
null::respawn:/bin/nice -n -1 /usr/sbin/inetd -f
null::respawn:/bin/nice -n -3 /usr/bin/filemgr
null::respawn:/usr/sbin/clksync 2
null::respawn:/usr/sbin/crond -f

# Stuff to do for the 3-finger salute
::ctrlaltdel:/sbin/reboot

# Stuff to do before rebooting
null::shutdown:/etc/init.d/rcK
null::shutdown:/bin/umount -a -r
null::shutdown:/sbin/swapoff -a
~
~
~
~- /etc/inittab 1/52 1%
- /etc/inittab 2/52 3%
- /etc/inittab 3/52 5%
- /etc/inittab 4/52 7%
- /etc/inittab 5/52 9%
- /etc/inittab 6/52 11%
- /etc/inittab 7/52 13%
- /etc/inittab 8/52 15%
- /etc/inittab 9/52 17%
- /etc/inittab 10/52 19%
- /etc/inittab 11/52 21%
- /etc/inittab 12/52 23%
- /etc/inittab 13/52 25%
- /etc/inittab 14/52 26%
- /etc/inittab 15/52 28%
- /etc/inittab 16/52 30%
- /etc/inittab 17/52 32%
- /etc/inittab 18/52 34%
- /etc/inittab 19/52 36%
- /etc/inittab 20/52 38%
- /etc/inittab 21/52 40%
- /etc/inittab 22/52 42%
- /etc/inittab 23/52 44%
- /etc/inittab 24/52 46%
- /etc/inittab 25/52 48%
- /etc/inittab 26/52 50%
- /etc/inittab 27/52 51%
- /etc/inittab 28/52 53%
- /etc/inittab 29/52 55%
- /etc/inittab 30/52 57%
- /etc/inittab 31/52 59%
- /etc/inittab 32/52 61%
- /etc/inittab 33/52 63%
- /etc/inittab 34/52 65%
- /etc/inittab 35/52 67%
- /etc/inittab 36/52 69%
- /etc/inittab 37/52 71%
- /etc/inittab 38/52 73%nnunulnullnull:I /etc/inittab 38/52 73%_tapI /etc/inittab [Modified] 38/52 73%- /etc/inittab [Modified] 38/52 73%:wq!"/etc/inittab" 52L, 1795C# kill -HUP 1
# 
# 
# 
# satc## satcomm &
satcomm[5686]: Warning: Option 'NAME' not valid at line 49

Interface type: ax5042
satcomm[5686]: TODO: Adjusting Routing Tables...

satcomm[5686]: UHF reprogramming device 1
BoarCant skip auto-ranging...
d R6, batch 1, serial 14; crystal: 15998121

SN: 41477
Warning: usQ 1: Freq: 494979217, FEC: 0
ing ideal crystal value.  probably incorrect.
Programming queue 1
libqnum: 1, 96
# Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!

# Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
Auto-ranging failed (cnt: 0, reg: 0x2B)!
failed reprogramming 1
Error programming comm params: No such file or directory
Carrier: 467994000.000000
Crystal: 15998121.000000
Bitrate: 9600
h: 1.000000
TMGCORRFRAC: 32
Encoding: NRZI+Scrambled
Modulation: FSK
FEC: Off
Framing: HDLC
CRC: CCITT
satcomm[5686]: No such file or directory - Failed to program radio in ax5042_program_rf_params_int() at ax5042_driver.c:630

satcomm[5686]: Unable to init radio!


[1]+  Done(4)                    satcomm
# 
# piomn###ng 1.1\####1.1.1.1
PING 1.1.1.1 (1.1.1.1): 56 data bytes
ping: sendto: Network is unreachable
# halt
# The system is going down NOW!
Sent SIGTERM to all processes
Sent SIGKILL to all processes
RequesSystem halted.
