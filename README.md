# Acer-605---Big-Sur
Big Sur Hackintosh for Acer 605

Specs:

- Intel Core i7 4790
- MS-7829 motherboard LGA1150
- Sapphire Nitro+ Radeon RX 590 8GB GDDR5 UEFI
- BCM94352HMB 802.11ac WiFi Bluetooth 867Mbps Wireless-AC WiFi + BT 4,0 half Mini PCI-E
- SSD LVCARDS 256GB fow Mac OS Big Sur

Follow this guide to install MacOS Big Sur: (Thanks to MaLd0n)

Before booting up from Big Sur, copy my EFI folder to the EFI partition, mounted with Clover Configurator, again thanks to MaLd0n for having uploaded the EFI for Haswell CPU. This was the base for my PC.

https://www.olarila.com/topic/8977-guide-installrestore-bigsur-with-opencore/

Do not forget to resize the SSD, at the end of the guide.

Reboot and boot OpenCore from the SSD. It takes a while. Password is 1234, as mentioned in the guide.

Open System Preferencies-> Software Update and update to Beta 2. Over 30 minutes to complete, do not power off the PC.

Boot again from OpenCore in SSD with the same password.
