%{TOC}

# Intro


# Basic Functions

This is a quite capable router, but of course one could always wish for more flash and RAM.

Info copied from: https://wiki.openwrt.org/toh/buffalo/wzr-hp-g301h

Architecture: MIPS  
Vendor: Atheros  
Bootloader: AR9132  
System-On-Chip: Atheros AR9132 rev 2  
CPU/Speed 400 Mhz (MIPS 24Kc)  
Flash-Chip: WZR-HP-G301NH  
Flash size: 32 MiB  
RAM: 64 MiB   
Wireless: Atheros AR9100 MAC/BB Rev:7 AR2133 RF Rev:a2  
Ethernet: RealTek RTL8366RB Gigabit w/ vlan support (4X1)  
USB: Yes 1 x 2.0  

# Supported Profiles
# Hardware Dependent features
# Table Of Content
# Index
# Things I learned
* Do not flash with WiFi on. Radio interference may affect contents so you will have to flash again.
* If you have problems using vi (vi: No terminal database found) through ssh, try setting TERM=xterm.
* If SSH does not start automatically at boot, enable ssh spawning through inetd.conf.

# Contacts
You will need some patches to run this board with FreeBSD current. Please contact me if you wish to do so.
