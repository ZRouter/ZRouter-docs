
%{TOC}

# Intro


# Basic Functions

Info copied from: https://wikidevi.com/wiki/Buffalo_WZR2-G300N

Architecture: ARM  
Vendor: Ralink  
Bootloader: U-BOOT  
System-On-Chip: RT1310  
CPU/Speed 320 Mhz  
Flash-Chip:   
Flash size: 4 MiB  
RAM: 16 MiB   
Wireless:   
Ethernet: Builtin two port(fv) 
Ethernet switch: IP175C
USB: No  

# Supported Profiles
# Hardware Dependent features
# Table Of Content
# Index
# Things I learned

# Contacts
You will need some patches to run this board with FreeBSD current. Please contact me if you wish to do so.

# Flash

```
5VT1310-EVB# tftpboot 00800000 Buffalo_WZR2-G300N.zimage
5VT1310-EVB# erase 0x1F010000 0x1F3CFFFF
5VT1310-EVB# cp.b 800000 0x1F010000 $(filesize)
```

also setenv to ipaddr and serverip for your network.
