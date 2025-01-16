# BIOS Settings Documentation

## Basic Information
- BIOS Version: 706
- Motherboard Model: X870E Hero Asus
- Amazon full title: ASUS ROG Crosshair X870E Hero AMD X870E AM5 ATX Motherboard, Advanced AI PC Ready, 18+2+2 Power Stages, DDR5, PCIe® 5.0, 5X M.2, Wi-Fi 7, USB4®, AI Overclocking, Core Flex, PCIe Slot Q-Release Slim
- Amazon link: https://www.amazon.com/dp/B0DDZSP2BG?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1

## Settings By Top Level Page
### Extreme Tweaker
- AI Overclock Tuner: EXPO II 
- EXPO: DDR5-6400 30-39-39-102-1.40v-1.40v 
- ECLK Mode: Auto 
- BCLK1 Frequency: 100.00000 
- Memory Frequency: DDR5-6200 (6400 is stable but FCLK 2133 is not)
- FCLK Frequency: 2067 (pairs with 6200 for latency)
- Core Tunings Configuration For Gaming: Auto
- Core Performance Boost: Enabled
- CPU Core Ratio: Auto
- CPU Core Ratio (Per CCX): Auto
- Turbo Game Mode: Disabled
- DRAM Timing Control: Refer to /Memory/

### Extreme Tweaker -> Precision Boost Overdrive
- Prochot VRM Throttling: Auto
- Peak Current Control: Auto
- Medium Load Boostit: Enabled
- Precision Boost Overdrive: Enabled
- Disable Current Limiter: Auto
- Precision Boost Overdrive Scalar: Manual
- Customized Precision Boost Overdrive Scalar: 4x (1x or 2x is default, some folks do 10x, im weary of this so 4x is the compromise)
- CPU Boost Clock Override: Enabled(Positive)
- Max CPU Boost Clock Override (+200)
- Per Core Boost Clock Limit: Auto (this can be used to limit when boosting on ECLK or if you have a core that is underperforming)
- Platform Thermal Throttle Limit: Auto
- Curve Optimizer: All cores -20 (This is entirely cpu and cooling dependent) (Random stutters or pc turns off means decrease the negative offset)
- Curve Shaper: Auto (This is pretty powerful and if im doing ECLK you can do some pretty awesome tuning)
- CO Load Guard: Auto

### Advanced
#### Advanced -> Trusted Computing
- Security Device Support: Disabled
- Disable Block Sid: Disabled
#### Advanced -> AMD fTPM Configuration
- Firmware TPM Switch: Enable Firmware TPM
- Erase fTPM NV for factory reset: Enabled
#### Advanced -> EUFI Variable Protection
- Password Protection of Runtime Variables: Enable
#### Advanced -> CPU Configuration
- PSS Support: Enabled
- NX Mode: Enabled
- SVM Mode: Disabled (disables hyper-v dont do this if you do virtualization but it adds memory latency a little bit)
#### Advanced -> PCI Subsystem Timings
- Above 4G Decoding: Enabled
- Resize Bar Support: Enabled
- SR-IOV Support: Disabled
#### Advanced -> USB Configuration
- Legacy USB Support: Enabled
- XHCI Hand-off: Enabled
- USB Mass Storage Driver Support: Enabled
- USB Single Port Control: Auto
#### Advanced -> Network Stack Configuration
- Network Stack: Disabled
#### Advanced -> NVMe Controller and Drive Information
- I have my SSD a Samsung SSD 990 PRO TB listed here, set to auto
#### Advanced -> HDD/SSD Smart Information
- Device: N/A
#### Advanced -> SATA Configuration
- SATA Controller: Disable if no sata devices otherwise Auto
- NVME Raid Mode: Disabled
- Smart self test: Enabled
#### Advanced -> APM Configuration
- Restore AC Power Loss: Power Off
- ErP Ready: Disabled
- Max Power Saving: Disabled
- Power On By PCI-E: Disabled
- Power On By RTC: Disabled
#### Onboard Devices Configuration
- Native ASPM: Auto
- CPU PCIE ASPM Mode Control: Auto
- PCIEX16_1 Bandwidth Bifurcation Configuration: PCIE 16X Mode unless you have multiple PCIE devices then auto
- PCIEX16_2 Banwidth Bifurcation Configuration: Auto Mode
- USB Audio Controller: Disabled (I have a GOXLR, enable if you use your motherboard usb audio controller)
- Realtek LAN Controller: Enabled (enable the one you use and disable the one you dont)
- Intel LAN Controller: Disable (enable the one you use and disable the one you dont)
- Wi-FI Controller: Disabled (Disabled because im hard wired, enable if you need)
- Bluetooth Controller: Disabled (I dont use bluetooth enable if you use)
- LED Lighting/When system is in a working state: Stealth Mode(enable if you like RGB)
- USB Power Delivery in Soft Off State(S5): Enabled
- Alteration Mode Switch: PCIE Link Speed
- PCIE Link Speed: All Auto

### Monitor
- I have everything on auto in this section

### Boot
- CSM: Disabled
- Secure Boot: Auto (Windows UEFI Mode/Standard)
#### Boot -> Boot Configuration
- Fast Boot: Disabled
- Boot Logo Display: Auto
- Post Delay Time: 3 sec (can increase if you want more time)
- Bootup NumLock State: On
- Wait for F1 if Error: Enabled
- Optional ROM Message: Force BIOS
- Interrupt 19 Capture: Disabled
- AMI Native NVMe Driver Support: Enabled
- Setup Mode: Advanced Mode

### Tools
- All Auto
