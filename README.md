# OpenCore-EFI
### OpenCore's EFI for Asus X555UA 
#### System Information:
+ Laptop model: Asus X555UA
+ CPU: Core i5-6200U
+ iGPU: Intel HD Graphic 520
+ Audio: ALC256
+ Trackapd: I2C-ELAN1000
+ Wifi and Ethernet: Realtek
#### Hakintosh:
+ OpenCore bootloader v0.5.9
+ MacOS Catalina 10.15.6
#### What's works:
+ Display Brightness
+ Audio (alcid=28)
+ iGPU
+ Trackpad with full gestsures (Required patch DSDT with I2C Controller's patch)
+ Keyboard
+ CPU Power Management (CPUFriend)
+ Battery Indicator (Required patch DSDT)
fixing ...
#### What's not works:
+ Wifi (Require DW1550 or anything else)
...
