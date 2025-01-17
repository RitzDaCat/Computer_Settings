# Windows 11 Performance Optimizations

A comprehensive list of modifications and tweaks applied to enhance Windows 11 performance that I am currently running.

## System Modifications

### Services Optimizations
- [x] Disabled Windows Search
- [ ] Disabled Windows Update
- [ ] Disabled SysMain (Superfetch)
- [ ] Disabled Windows Defender (Use at your own risk)

### Visual Effects


### Power Settings
- [ ] Set Power Plan to "High Performance"

### Memory Optimization

### Gaming Optimizations
- [ ] Enabled Game Mode
- [ ] Enabled Hardware-Accelerated GPU Scheduling

### Network Optimizations
- [ ] Disabled energy efficient options on NIC like green energy etc

### Privacy & Telemetry
- [ ] Disabled Telemetry
- [ ] Disabled Background Apps
- [ ] Disabled App Diagnostics
- [ ] ^ did all of this with https://www.oo-software.com/en/shutup10

## Registry Tweaks
```registry
; Add registry modifications here as they are implemented
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\PriorityControl]
"Win32PrioritySeparation"=dword:00000026
```

## Scheduled Tasks
- [ ] Disabled unnecessary scheduled tasks
- [ ] Modified task trigger times
- [ ] Disabled telemetry tasks

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
