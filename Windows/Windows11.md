# Windows 11 Performance Optimizations

A comprehensive list of modifications and tweaks applied to enhance Windows 11 performance.
Will mark items that I am currently running with a X and items listed without an X means they are noted
as items to research and test but im not currently running.

## System Modifications

### Services Optimizations

### Visual Effects


### Power Settings
- [x] Set Power Plan to "High Performance"

### Memory Optimization

### Gaming Optimizations
- [ ] Enabled Game Mode
- [ ] Enabled Hardware-Accelerated GPU Scheduling

### Network Optimizations
- [ ] Disabled energy efficient options on NIC like green energy etc

### Privacy & Telemetry
- [x] Disabled Telemetry
- [x] Disabled App Diagnostics
- [x] ^ did all of this with https://www.oo-software.com/en/shutup10

## Registry Tweaks
```registry
; Add registry modifications here as they are implemented
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\PriorityControl]
"Win32PrioritySeparation"=dword:00000026
```

## Scheduled Tasks
- [x] Disabled unnecessary scheduled tasks
- [x] Modified task trigger times
- [x] Disabled telemetry tasks

## Notes
- Backup system before applying any modifications
- Create restore point before registry modifications
- Document any issues or improvements
- Test system stability after changes

## Results
| Modification | Before | After | Impact |
|--------------|---------|--------|---------|
| Example Tweak | X ms | Y ms | Z% improvement |

---

Last Updated: [Date]
