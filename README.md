# OpenCore-EFI
> Link for full guide: https://dortania.github.io/OpenCore-Install-Guide/
### OpenCore's EFI for Asus X555UA
#### System Information:
+ Laptop model: Asus X555UA
+ CPU: Core i5-6200U
+ iGPU: Intel HD Graphic 520
+ Audio: ALC256
+ Trackapd: I2C-ELAN1000
+ Wifi and Ethernet: Realtek
#### Hakintosh:
+ OpenCore bootloader v0.6.7
+ <strong>Big Sur</strong> dual-boot with Windows 10
#### What's works:
+ Adjust Brightness
+ Audio (alcid=28)
+ iGPU
+ Trackpad with full gestures (Required patch DSDT with I2C Controller's patch)
+ Keyboard (fn key still not working)
+ CPU Power Management (CPUFriend)
+ Battery Indicator (Required patch DSDT)

fixing ...
#### What's not works:
+ Wifi and Bluetooth (Require DW1550 or anything else)

...
