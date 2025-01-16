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

### Precision Boost Overdrive
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

