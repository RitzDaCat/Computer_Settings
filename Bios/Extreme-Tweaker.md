# Extreme Tweaker

- **AI Overclock Tuner:** EXPO II
- **EXPO:** DDR5-6400 30-39-39-102-1.40v-1.40v
- **ECLK Mode:** Auto
- **BCLK1 Frequency:** 100.00000
- **Memory Frequency:** DDR5-6200 (6400 is stable but FCLK 2133 is not)
- **FCLK Frequency:** 2067 (pairs with 6200 for latency)
- **Core Tunings Configuration For Gaming:** Auto
- **Core Performance Boost:** Enabled
- **CPU Core Ratio:** Auto
- **CPU Core Ratio (Per CCX):** Auto
- **Turbo Game Mode:** Disabled
- **DRAM Timing Control:** Refer to /Memory/

## Precision Boost Overdrive
- **Prochot VRM Throttling:** Auto
- **Peak Current Control:** Auto
- **Medium Load Boostit:** Enabled
- **Precision Boost Overdrive:** Enabled
- **Disable Current Limiter:** Auto
- **Precision Boost Overdrive Scalar:** Manual
- **Customized Precision Boost Overdrive Scalar:** 4x (1x or 2x is default, some folks do 10x, im weary of this so 4x is the compromise)
- **CPU Boost Clock Override:** Enabled(Positive)
- **Max CPU Boost Clock Override:** (+200)
- **Per Core Boost Clock Limit:** Auto (this can be used to limit when boosting on ECLK or if you have a core that is underperforming)
- **Platform Thermal Throttle Limit:** Auto
- **Curve Optimizer:** All cores -20 (This is entirely cpu and cooling dependent) (Random stutters or pc turns off means decrease the negative offset)
- **Curve Shaper:** Auto (This is pretty powerful and if im doing ECLK you can do some pretty awesome tuning)
- **CO Load Guard:** Auto

## DIGI + VRM
- **VRM Initialization Check:** Enabled
- **Voltage Training:** Auto
- **CPU Load-line Calibration:** Auto
- **Segment2 Loadline:** Auto
- **CPU Current Reporting Scale:** Auto
- **Core Voltage Suspension:** Auto
- **CPU VRM Switching Frequency:** Auto
- **VRM Spread Spectrum:** Disabled (My understanding is spread spectrum causes minor performance variations)
- **CPU Power Duty Control:** Extreme (Extreme is more phases, I paid for a nice MB so want to use them right?)
- **CPU Power Phase Control:** Extreme
- **VDDSOC Current Reporting Scale:** Auto
- **VDDSOC Switching Frequency:** Auto
- **VDDSOC Power Phase Control:** Extreme
- **DRAM Switching Frequency:** Auto
- **DRAM Power Phase Control:** Extreme
- **MISC Switching Frequency:** Auto
