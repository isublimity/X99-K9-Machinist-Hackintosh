# X99-K9-Machinist-Hackintosh

Machinist X99-K9 Hackintosh

This repo backup for my opencore 0.7.0 settings.

Other good links:

* [Andrej-Antipov/X99-K9-Machinist-Hackintosh](https://github.com/Andrej-Antipov/X99-K9-Machinist-Hackintosh)
* [markkpa / x99-t8d-and-x99-f8d-Opencore-Hackintosh](https://github.com/markkpa/x99-t8d-and-x99-f8d-Opencore-Hackintosh)
* [Настройка BIOS Huananzhi-F8D README-rus.md ](https://github.com/tarkh/hackintosh/blob/main/Huananzhi-F8D/README-rus.md)
* [Koshak1013 / HuananzhiX99_BIOS_mods](https://github.com/Koshak1013/HuananzhiX99_BIOS_mods)


### Config 

- BCM943602CS - Wi-Fi & Bluetooth
- MACHINIST X99-k9 
- Intel(R) Xeon(R) CPU E5-2673 v3
- DIMM Samsung 2133 MT/s 4x8ГБ
- Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter
- AMD Radeon RX 570 4Gb

- macOS Big Sur Версия 11.4 (Выпуск 20F71)

### Changelog 

* 2021-11 - Big Sur
* 2022-07 - Big Sur,try merge Andrej-Antipov conf
* 2022-07 - `sudo pmset -a proximitywake 0`



### Power settings
```
$ pmset -g

System-wide power settings:
Currently in use:
hibernatemode        0
powernap             1
womp                 1
networkoversleep     0
sleep                0
Sleep On Power Button 1
proximitywake        1
hibernatefile        /var/vm/sleepimage
ttyskeepawake        1
disksleep            10
displaysleep         25

```


### System Info
```
-----------------------------------------------------------------------
System Info
-----------------------------------------------------------------------
Host                           iMac.local
OS                             macOS Big Sur Версия 11.4 (Выпуск 20F71)
Kernel                         Darwin 20.5.0 x86_64
RAM                            32.00 GB
Model Identifier               iMacPro1,1
CPU                            Intel(R) Xeon(R) CPU E5-2673 v3 @ 2.40GHz
Intel Generation               ???
Platform ID                    0x00000000
Board ID                       Mac-7BA5B2D9E42DDD94 
FW Version                     1554.100.64.0.0 
Serial Number                  Default string
Hardware UUID                  00020003-0004-0005-0006-000700080009
System ID                      ???
ROM                            0000000FA28B
Board Serial Number            uMk
VDA Decoder                    Fully Supported
-----------------------------------------------------------------------
Serial Info
-----------------------------------------------------------------------
Country                        Ireland (Cork)
Year                           0
Line                           0 (copy 1)
Model                          ???
Model Identifier               MacBook1,1
Valid                          Unlikely
-----------------------------------------------------------------------
GFX0
-----------------------------------------------------------------------
GPU Name                       Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]
GPU Device ID                  0x67DF1002
Quartz Extreme (QE/CI)         Yes
Metal Supported                Yes
Metal Device Name              AMD Radeon RX 570
Metal Default Device           Yes
Metal Low Power                No
Metal Headless                 No
-----------------------------------------------------------------------


```