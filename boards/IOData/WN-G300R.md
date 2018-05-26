# Flash

```
ar7240> setenv ipaddr 10.10.10.99
ar7240> setenv serverip 10.10.10.3
ar7240> tftp 0x80060000 IOData_WN-G300R.zimage
ar7240> erase 0x9f040000 +$filesize
ar7240> cp.b 0x80060000 0x9f040000 $filesize
ar7240> reset
```
