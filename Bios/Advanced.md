# Advanced

## Trusted Computing
- **Security Device Support:** Disabled
- **Disable Block Sid:** Disabled

## AMD fTPM Configuration
- **Firmware TPM Switch:** Enable Firmware TPM
- **Erase fTPM NV for factory reset:** Enabled

## EUFI Variable Protection
- **Password Protection of Runtime Variables:** Enable

## CPU Configuration
- **PSS Support:** Enabled
- **NX Mode:** Enabled
- **SVM Mode:** Disabled (disables hyper-v dont do this if you do virtualization but it adds memory latency a little bit)

## PCI Subsystem Timings
- **Above 4G Decoding:** Enabled
- **Resize Bar Support:** Enabled
- **SR-IOV Support:** Disabled

## USB Configuration
- **Legacy USB Support:** Enabled
- **XHCI Hand-off:** Enabled
- **USB Mass Storage Driver Support:** Enabled
- **USB Single Port Control:** Auto

## Network Stack Configuration
- **Network Stack:** Disabled

## NVMe Controller and Drive Information
- I have my SSD a Samsung SSD 990 PRO TB listed here, set to auto

## HDD/SSD Smart Information
- **Device:** N/A

## SATA Configuration
- **SATA Controller:** Disable if no sata devices otherwise Auto
- **NVME Raid Mode:** Disabled
- **Smart self test:** Enabled

## APM Configuration
- **Restore AC Power Loss:** Power Off
- **ErP Ready:** Disabled
- **Max Power Saving:** Disabled
- **Power On By PCI-E:** Disabled
- **Power On By RTC:** Disabled

## Onboard Devices Configuration
- **Native ASPM:** Auto
- **CPU PCIE ASPM Mode Control:** Auto
- **PCIEX16_1 Bandwidth Bifurcation Configuration:** PCIE 16X Mode unless you have multiple PCIE devices then auto
- **PCIEX16_2 Banwidth Bifurcation Configuration:** Auto Mode
- **USB Audio Controller:** Disabled (I have a GOXLR, enable if you use your motherboard usb audio controller)
- **Realtek LAN Controller:** Enabled (enable the one you use and disable the one you dont)
- **Intel LAN Controller:** Disable (enable the one you use and disable the one you dont)
- **Wi-FI Controller:** Disabled (Disabled because im hard wired, enable if you need)
- **Bluetooth Controller:** Disabled (I dont use bluetooth enable if you use)
- **LED Lighting/When system is in a working state:** Stealth Mode(enable if you like RGB)
- **USB Power Delivery in Soft Off State(S5):** Enabled
- **Alteration Mode Switch:** PCIE Link Speed
- **PCIE Link Speed:** All Auto
