# ASUS ROG STRIX Z370-i Gaming Hackintosh
# Hardware

name | spec
---|---
MB | ASUS ASUS ROG STRIX Z370-i Gaming ITX
CPU| i7 8700K
Cooler|Coolstar
Wifi|Replace to Apple BCM943602CS
Memery| Kingston hyperx 2666 16G*2
SSD | Samsung SM961 512GB

# WORKING

> Wi-Fi ( Onboard WiFi card was replaced, see components list above )  

> Bluetooth

> Ethernet Port

> Sound

> NVMe SM961 / Trim

> i7-8700 ( six-physical cores and 6 virtual - HT )

> Intel UHD630 (configured with DisplayPort attached to Asus board)

> Sleep

> Power Management and P-States

> USB 3.0

> USB 2.0

> HandOff

> AirDrop

> iMessages

> iCloud

> AirPlay

> iBooks

> Personal Hotspot

# BIOS Settings
**Save & Exit → Load Optimized Defaults**

 - F2 to enter BIOS on Asus Z370 Strix 2 - Switch to Advanced Mode F7

 - Exit → Load Optimized Defaults : Yes

 - Advanced \ PCH Configuration → IOAPIC 24-119 Entries : Enabled

 - Advanced \ APM Configuration → Power On By PCI-E/PCI : Disabled

 - Advanced \ Network Stack Configuration → Network Stack : Disabled

 - Advanced \ USB Configuration → Legacy USB Support : Auto ( needs to be auto for SSDT-UIAC.aml to work )

 - Boot → Fast Boot : Disabled

 - Boot → Secure Boot → OS Type : Other OS

 - Boot → CSM : Disabled ( Only enable if using dual monitor setup)

 - Ai Tweaker → Asus MultiCore Enhancement: Disable ( but only if you have intel stock CPU cooler ! )

 - Integrated Graphics : Enabled

# Update Log

  ## 2018-10-07
 - Catalina 10.15 Public Beta2

---
